# Function: <code>mmc_switch_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff816c2350)
Location: drivers/mmc/core/mmc.c:1044
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
```
**Symbols:**

```
ffffffff816c2350-ffffffff816c23a3: mmc_switch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817250e0)
Location: drivers/mmc/core/mmc.c:1004
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff817250e0-ffffffff81725133: mmc_switch_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175c31f)
Location: drivers/mmc/core/mmc_ops.c:448
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff8175c0c0-ffffffff8175c0d5: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177a5f4)
Location: drivers/mmc/core/mmc_ops.c:443
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff8177a4a0-ffffffff8177a4b5: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0a44)
Location: drivers/mmc/core/mmc_ops.c:444
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff817f08f0-ffffffff817f0905: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81839e6a)
Location: drivers/mmc/core/mmc_ops.c:444
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff81839c20-ffffffff81839c35: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81865e9a)
Location: drivers/mmc/core/mmc_ops.c:444
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff81865c50-ffffffff81865c65: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818a9cd5)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff818a9a90-ffffffff818a9aa5: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818dc129)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff818dbed0-ffffffff818dbee5: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card, bool crc_err_fatal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819aee47)
Location: drivers/mmc/core/mmc_ops.c:434
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff819aec30-ffffffff819aec9e: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card, bool crc_err_fatal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b14a7)
Location: drivers/mmc/core/mmc_ops.c:434
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff819b1290-ffffffff819b12fe: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card, bool crc_err_fatal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81995cb5)
Location: drivers/mmc/core/mmc_ops.c:413
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff81995a80-ffffffff81995aee: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card, bool crc_err_fatal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a41b0f)
Location: drivers/mmc/core/mmc_ops.c:417
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff81a418e0-ffffffff81a4194e: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card, bool crc_err_fatal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81baf1c0)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff81baef60-ffffffff81baefdf: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card, bool crc_err_fatal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d52b9a)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff81d528f0-ffffffff81d5296f: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card, bool crc_err_fatal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbd54a)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff81dbd300-ffffffff81dbd37f: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card, bool crc_err_fatal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75b7a)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff81e75930-ffffffff81e759af: mmc_switch_status (STB_GLOBAL)
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
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b36248)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffff800010b35fe8-ffff800010b36018: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c10cec)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
c0c10a60-c0c10a80: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c31300)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
c000000000c31090-c000000000c310a8: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e412)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffe00070e262-ffffffe00070e28e: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187fae9)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff8187f890-ffffffff8187f8a5: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818d0f89)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff818d0d30-ffffffff818d0d45: mmc_switch_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch_status(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818edaa9)
Location: drivers/mmc/core/mmc_ops.c:446
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
```
**Symbols:**

```
ffffffff818ed850-ffffffff818ed865: mmc_switch_status (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool crc_err_fatal</code>
</li>
</ul>
</details>
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
