# Function: <code>usb_phy_roothub_power_off</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff8176d170)
Location: drivers/usb/core/phy.c:152
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff8176d170-ffffffff8176d1ac: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817917c0)
Location: drivers/usb/core/phy.c:153
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817917c0-ffffffff817917fc: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817cfff0)
Location: drivers/usb/core/phy.c:181
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817cfff0-ffffffff817d002c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81800e70)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff81800e70-ffffffff81800eac: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff818d1655)
Location: drivers/usb/core/phy.c:202
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818d1550-ffffffff818d158c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff818dba35)
Location: drivers/usb/core/phy.c:202
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818db930-ffffffff818db96c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff818bedf5)
Location: drivers/usb/core/phy.c:202
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818becf0-ffffffff818bed2c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81955455)
Location: drivers/usb/core/phy.c:202
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81955350-ffffffff8195538c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81aaedf5)
Location: drivers/usb/core/phy.c:202
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81aaecc0-ffffffff81aaed0c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81c368d5)
Location: drivers/usb/core/phy.c:202
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c36770-ffffffff81c367bc: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81c9dbc5)
Location: drivers/usb/core/phy.c:202
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c9da60-ffffffff81c9daac: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81d52775)
Location: drivers/usb/core/phy.c:202
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81d52610-ffffffff81d5265c: usb_phy_roothub_power_off (STB_GLOBAL)
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
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffff800010a35068)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffff800010a35068-ffff800010a350bc: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (c0b08788)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
c0b08788-c0b087d0: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (c000000000af2b70)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
c000000000af2b70-c000000000af2bf8: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffe00065287c)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffe00065287c-ffffffe0006528c0: usb_phy_roothub_power_off (STB_GLOBAL)
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
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817b9250)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817b9250-ffffffff817b928c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817aac80)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817aac80-ffffffff817aacbc: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817f5cf0)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817f5cf0-ffffffff817f5d2c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff8180ff30)
Location: drivers/usb/core/phy.c:202
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff8180ff30-ffffffff8180ff6c: usb_phy_roothub_power_off (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
