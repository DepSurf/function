# Function: <code>phy_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8141bfc0)
Location: drivers/phy/phy-core.c:429
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff8141bfc0-ffffffff8141bff7: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81464620)
Location: drivers/phy/phy-core.c:444
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81464620-ffffffff81464657: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81483920)
Location: drivers/phy/phy-core.c:459
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81483920-ffffffff81483957: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8148d53d)
Location: drivers/phy/phy-core.c:459
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff8148dde0-ffffffff8148de18: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814c968d)
Location: drivers/phy/phy-core.c:478
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff814c9f40-ffffffff814c9f78: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814faead)
Location: drivers/phy/phy-core.c:498
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff814fa680-ffffffff814fa6b7: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8150f2fd)
Location: drivers/phy/phy-core.c:562
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff8150f900-ffffffff8150f937: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8153d140)
Location: drivers/phy/phy-core.c:564
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff8153d140-ffffffff8153d1ae: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8155df50)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff8155df50-ffffffff8155dfbe: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct device *dev, struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff816000be)
Location: drivers/phy/phy-core.c:596
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81600080-ffffffff816000a1: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct device *dev, struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81624fae)
Location: drivers/phy/phy-core.c:596
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81624f70-ffffffff81624f91: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct device *dev, struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8160895e)
Location: drivers/phy/phy-core.c:626
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81608920-ffffffff81608941: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct device *dev, struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8167759e)
Location: drivers/phy/phy-core.c:626
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81677560-ffffffff81677581: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct device *dev, struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff817926bd)
Location: drivers/phy/phy-core.c:664
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81792680-ffffffff817926a8: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct device *dev, struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818a715d)
Location: drivers/phy/phy-core.c:664
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff818a7110-ffffffff818a7138: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct device *dev, struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818e9fcd)
Location: drivers/phy/phy-core.c:666
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff818e9f80-ffffffff818e9fa8: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void phy_put(struct device *dev, struct phy *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8193146d)
Location: drivers/phy/phy-core.c:666
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81931420-ffffffff81931448: phy_put (STB_GLOBAL)
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
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffff800010686768)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffff800010686768-ffff8000106867d4: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c082a510)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
c082a510-c082a578: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c0000000008213d0)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
c0000000008213d0-c00000000082147c: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffe000496402)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffe000496402-ffffffe00049646a: phy_put (STB_GLOBAL)
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
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81556540)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81556540-ffffffff815565ae: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81546a00)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81546a00-ffffffff81546a6e: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81552280)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff81552280-ffffffff815522ee: phy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void phy_put(struct phy *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8156c110)
Location: drivers/phy/phy-core.c:574
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_release
```
**Symbols:**

```
ffffffff8156c110-ffffffff8156c17e: phy_put (STB_GLOBAL)
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
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>phy</code> ➡️ <code>dev, phy</code>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
