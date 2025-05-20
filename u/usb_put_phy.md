# Function: <code>usb_put_phy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81620b90)
Location: drivers/usb/phy/phy.c:360
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
```
**Symbols:**

```
ffffffff81620b90-ffffffff81620bbe: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81681550)
Location: drivers/usb/phy/phy.c:360
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff81681550-ffffffff8168157e: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff816af280)
Location: drivers/usb/phy/phy.c:360
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff816af280-ffffffff816af2ae: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff816c4775)
Location: drivers/usb/phy/phy.c:408
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff816c46e0-ffffffff816c4708: usb_put_phy.part.12 (STB_LOCAL)
ffffffff816c4710-ffffffff816c4727: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81730828)
Location: drivers/usb/phy/phy.c:676
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff81730790-ffffffff817307b8: usb_put_phy.part.15 (STB_LOCAL)
ffffffff817307c0-ffffffff817307d7: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff8176fab8)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff8176fa20-ffffffff8176fa48: usb_put_phy.part.16 (STB_LOCAL)
ffffffff8176fa50-ffffffff8176fa66: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81794138)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff817940a0-ffffffff817940c8: usb_put_phy.part.16 (STB_LOCAL)
ffffffff817940d0-ffffffff817940e6: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817d29d8)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff817d2940-ffffffff817d2967: usb_put_phy.part.0 (STB_LOCAL)
ffffffff817d2970-ffffffff817d2986: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff818038a8)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff81803810-ffffffff81803837: usb_put_phy.part.0 (STB_LOCAL)
ffffffff81803840-ffffffff81803856: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff818d3cfa)
Location: drivers/usb/phy/phy.c:606
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff818d4170-ffffffff818d419f: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff818de09a)
Location: drivers/usb/phy/phy.c:606
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff818de510-ffffffff818de53f: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff818c13fa)
Location: drivers/usb/phy/phy.c:606
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff818c1830-ffffffff818c185f: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81957c0a)
Location: drivers/usb/phy/phy.c:644
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff81958050-ffffffff8195807f: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81ab19c8)
Location: drivers/usb/phy/phy.c:644
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff81ab1e90-ffffffff81ab1ece: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81c39f28)
Location: drivers/usb/phy/phy.c:644
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff81c3a4b0-ffffffff81c3a4ee: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81ca12c8)
Location: drivers/usb/phy/phy.c:644
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff81ca1860-ffffffff81ca189e: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81d55f18)
Location: drivers/usb/phy/phy.c:644
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff81d564b0-ffffffff81d564ee: usb_put_phy (STB_GLOBAL)
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
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffff800010a380a4)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffff800010a37fd8-ffff800010a38014: usb_put_phy.part.0 (STB_LOCAL)
ffff800010a38018-ffff800010a38048: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (c0b0b26c)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
c0b0b1c0-c0b0b1f0: usb_put_phy.part.0 (STB_LOCAL)
c0b0b1f0-c0b0b214: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (c000000000af6b4c)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
c000000000af6a60-c000000000af6ab4: usb_put_phy.part.0 (STB_LOCAL)
c000000000af6ac0-c000000000af6adc: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffe000654da4)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffe000654cea-ffffffe000654d22: usb_put_phy.part.0 (STB_LOCAL)
ffffffe000654d22-ffffffe000654d4e: usb_put_phy (STB_GLOBAL)
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
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817bbc88)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff817bbbf0-ffffffff817bbc17: usb_put_phy.part.0 (STB_LOCAL)
ffffffff817bbc20-ffffffff817bbc36: usb_put_phy (STB_GLOBAL)
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
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817f8728)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff817f8690-ffffffff817f86b7: usb_put_phy.part.0 (STB_LOCAL)
ffffffff817f86c0-ffffffff817f86d6: usb_put_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_put_phy(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81812968)
Location: drivers/usb/phy/phy.c:595
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
Direct callers:
  - drivers/usb/phy/phy.c:devm_usb_phy_release2
  - drivers/usb/phy/phy.c:devm_usb_phy_release
```
**Symbols:**

```
ffffffff818128d0-ffffffff818128f7: usb_put_phy.part.0 (STB_LOCAL)
ffffffff81812900-ffffffff81812916: usb_put_phy (STB_GLOBAL)
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
