# Function: <code>__usb_phy_get_charger_type</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817303e0)
Location: drivers/usb/phy/phy.c:147
Inline: False
```
**Symbols:**

```
ffffffff817303e0-ffffffff817304c2: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff8176f4e0)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff8176f4e0-ffffffff8176f5b3: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81793b60)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff81793b60-ffffffff81793c33: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817d2460)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff817d2460-ffffffff817d2529: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81803330)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff81803330-ffffffff818033f9: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff818d3e50)
Location: drivers/usb/phy/phy.c:139
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy_dev
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff818d3e50-ffffffff818d3f1c: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff818de1f0)
Location: drivers/usb/phy/phy.c:139
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy_dev
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff818de1f0-ffffffff818de2bc: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff818c1530)
Location: drivers/usb/phy/phy.c:139
Inline: True
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy_dev
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff818c1530-ffffffff818c15db: __usb_phy_get_charger_type.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81957d40)
Location: drivers/usb/phy/phy.c:177
Inline: True
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy_dev
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff81957d40-ffffffff81957deb: __usb_phy_get_charger_type.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81ab1b60)
Location: drivers/usb/phy/phy.c:177
Inline: True
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy_dev
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff81ab1b60-ffffffff81ab1c1a: __usb_phy_get_charger_type.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81c3a0f0)
Location: drivers/usb/phy/phy.c:177
Inline: True
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy_dev
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff81c3a0f0-ffffffff81c3a1aa: __usb_phy_get_charger_type.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81ca14a0)
Location: drivers/usb/phy/phy.c:177
Inline: True
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy_dev
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff81ca14a0-ffffffff81ca155a: __usb_phy_get_charger_type.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81d560f0)
Location: drivers/usb/phy/phy.c:177
Inline: True
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy_dev
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff81d560f0-ffffffff81d561aa: __usb_phy_get_charger_type.constprop.0 (STB_LOCAL)
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
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffff800010a37ad8)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_extcon
  - drivers/usb/phy/phy.c:usb_phy_get_charger_type
```
**Symbols:**

```
ffff800010a37ad8-ffff800010a37bb8: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (c0b0ac40)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_extcon
  - drivers/usb/phy/phy.c:usb_phy_get_charger_type
```
**Symbols:**

```
c0b0ac40-c0b0acfc: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (c000000000af61b0)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_extcon
  - drivers/usb/phy/phy.c:usb_phy_get_charger_type
```
**Symbols:**

```
c000000000af61b0-c000000000af62fc: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffe000654806)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_extcon
  - drivers/usb/phy/phy.c:usb_phy_get_charger_type
```
**Symbols:**

```
ffffffe000654806-ffffffe0006548a8: __usb_phy_get_charger_type (STB_LOCAL)
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
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817bb710)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff817bb710-ffffffff817bb7d9: __usb_phy_get_charger_type (STB_LOCAL)
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
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817f81b0)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff817f81b0-ffffffff817f8279: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __usb_phy_get_charger_type(struct usb_phy *usb_phy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff818123f0)
Location: drivers/usb/phy/phy.c:128
Inline: False
Direct callers:
  - drivers/usb/phy/phy.c:usb_add_phy
```
**Symbols:**

```
ffffffff818123f0-ffffffff818124b9: __usb_phy_get_charger_type (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
