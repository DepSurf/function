# Function: <code>usb_add_phy_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81620d20)
Location: drivers/usb/phy/phy.c:421
Inline: False
Direct callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
```
**Symbols:**

```
ffffffff81620d20-ffffffff81620df3: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff816816e0)
Location: drivers/usb/phy/phy.c:421
Inline: False
```
**Symbols:**

```
ffffffff816816e0-ffffffff816817b3: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff816af410)
Location: drivers/usb/phy/phy.c:421
Inline: False
```
**Symbols:**

```
ffffffff816af410-ffffffff816af4e3: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff816c4790)
Location: drivers/usb/phy/phy.c:473
Inline: True
```
**Symbols:**

```
ffffffff816c4790-ffffffff816c4872: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81730c10)
Location: drivers/usb/phy/phy.c:741
Inline: True
```
**Symbols:**

```
ffffffff81730c10-ffffffff81730d7b: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff8176fad0)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
ffffffff8176fad0-ffffffff8176fbdc: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81794150)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
ffffffff81794150-ffffffff8179425c: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817d2b5c)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
ffffffff817d2b5c-ffffffff817d2b74: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff817d29f0-ffffffff817d2ae7: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81803a2c)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
ffffffff81803a2c-ffffffff81803a44: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff818038c0-ffffffff818039b7: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (0)
Location: drivers/usb/phy/phy.c:672
Inline: False
```
**Symbols:**

```
ffffffff818d4247-ffffffff818d425f: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff818d4070-ffffffff818d416a: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (0)
Location: drivers/usb/phy/phy.c:672
Inline: False
```
**Symbols:**

```
ffffffff81c1ebb2-ffffffff81c1ebca: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff818de410-ffffffff818de50a: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (0)
Location: drivers/usb/phy/phy.c:672
Inline: False
```
**Symbols:**

```
ffffffff81c109e6-ffffffff81c109fe: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff818c15e0-ffffffff818c16da: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (0)
Location: drivers/usb/phy/phy.c:715
Inline: False
```
**Symbols:**

```
ffffffff81d17d30-ffffffff81d17d48: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff81957df0-ffffffff81957efb: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (0)
Location: drivers/usb/phy/phy.c:715
Inline: False
```
**Symbols:**

```
ffffffff81ee2bd9-ffffffff81ee2bf1: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff81ab1c20-ffffffff81ab1d37: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81c3a1c0)
Location: drivers/usb/phy/phy.c:715
Inline: False
```
**Symbols:**

```
ffffffff81c3a1c0-ffffffff81c3a2ec: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81ca1570)
Location: drivers/usb/phy/phy.c:715
Inline: False
```
**Symbols:**

```
ffffffff81ca1570-ffffffff81ca169c: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81d561c0)
Location: drivers/usb/phy/phy.c:715
Inline: False
```
**Symbols:**

```
ffffffff81d561c0-ffffffff81d562ec: usb_add_phy_dev (STB_GLOBAL)
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
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffff800010a38848)
Location: drivers/usb/phy/phy.c:661
Inline: True
Direct callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
```
**Symbols:**

```
ffff800010a38848-ffff800010a38990: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (c0b0b3f0)
Location: drivers/usb/phy/phy.c:661
Inline: True
Direct callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
```
**Symbols:**

```
c0b0b3f0-c0b0b4e0: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (c000000000af6d70)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
c000000000af6d70-c000000000af6ed0: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffe000654ef2)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
ffffffe000654ef2-ffffffe000654fc0: usb_add_phy_dev (STB_GLOBAL)
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
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817bbe0c)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
ffffffff817bbe0c-ffffffff817bbe24: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff817bbca0-ffffffff817bbd97: usb_add_phy_dev (STB_GLOBAL)
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
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817f88ac)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
ffffffff817f88ac-ffffffff817f88c4: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff817f8740-ffffffff817f8837: usb_add_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_add_phy_dev(struct usb_phy *x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81812aec)
Location: drivers/usb/phy/phy.c:661
Inline: True
```
**Symbols:**

```
ffffffff81812aec-ffffffff81812b04: usb_add_phy_dev.cold (STB_LOCAL)
ffffffff81812980-ffffffff81812a77: usb_add_phy_dev (STB_GLOBAL)
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
