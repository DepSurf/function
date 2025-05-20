# Function: <code>usb_get_phy_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct usb_phy *usb_get_phy_dev(struct device *dev, u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81620fb0)
Location: drivers/usb/phy/phy.c:278
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
```
**Symbols:**

```
ffffffff81620fb0-ffffffff816210d4: usb_get_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct usb_phy *usb_get_phy_dev(struct device *dev, u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff81681960)
Location: drivers/usb/phy/phy.c:278
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
```
**Symbols:**

```
ffffffff81681960-ffffffff81681a6b: usb_get_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct usb_phy *usb_get_phy_dev(struct device *dev, u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff816af690)
Location: drivers/usb/phy/phy.c:278
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
```
**Symbols:**

```
ffffffff816af690-ffffffff816af79b: usb_get_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct usb_phy *usb_get_phy_dev(struct device *dev, u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff816c4880)
Location: drivers/usb/phy/phy.c:326
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
```
**Symbols:**

```
ffffffff816c4880-ffffffff816c498b: usb_get_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct usb_phy *usb_get_phy_dev(struct device *dev, u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy.c (ffffffff817309f0)
Location: drivers/usb/phy/phy.c:594
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy.c:devm_usb_get_phy_dev
```
**Symbols:**

```
ffffffff817309f0-ffffffff81730afb: usb_get_phy_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
