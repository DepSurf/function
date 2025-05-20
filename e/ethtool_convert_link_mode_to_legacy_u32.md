# Function: <code>ethtool_convert_link_mode_to_legacy_u32</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81788bf8)
Location: net/core/ethtool.c:404
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
**Symbols:**

```
ffffffff81787b20-ffffffff81787b40: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817b64a8)
Location: net/core/ethtool.c:415
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
**Symbols:**

```
ffffffff817b50e0-ffffffff817b5100: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817d510a)
Location: net/core/ethtool.c:418
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
**Symbols:**

```
ffffffff817d5040-ffffffff817d5060: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8184f64c)
Location: net/core/ethtool.c:431
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
**Symbols:**

```
ffffffff8184f5c0-ffffffff8184f5e0: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81899cbc)
Location: net/core/ethtool.c:410
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
**Symbols:**

```
ffffffff81899360-ffffffff81899375: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818bc700)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff818bc700-ffffffff818bc715: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81908ff0)
Location: net/core/ethtool.c:411
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81908ff0-ffffffff81909070: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8193b730)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff8193b730-ffffffff8193b7b0: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a81690)
Location: net/ethtool/ioctl.c:338
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81a81690-ffffffff81a81710: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8b280)
Location: net/ethtool/ioctl.c:342
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81a8b280-ffffffff81a8b300: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a74720)
Location: net/ethtool/ioctl.c:342
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81a74720-ffffffff81a747a0: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b2e970)
Location: net/ethtool/ioctl.c:344
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81b2e970-ffffffff81b2e9f0: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cb9770)
Location: net/ethtool/ioctl.c:369
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81cb9770-ffffffff81cb97f8: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e77618)
Location: net/ethtool/ioctl.c:362
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81e75390-ffffffff81e753c6: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed37a8)
Location: net/ethtool/ioctl.c:363
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_get_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_get_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_get_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_get_eee
```
**Symbols:**

```
ffffffff81ed1570-ffffffff81ed15a6: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f970b8)
Location: net/ethtool/ioctl.c:366
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_get_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_get_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_get_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_get_eee
```
**Symbols:**

```
ffffffff81f95050-ffffffff81f95086: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
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
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bd9758)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - drivers/net/mii.c:mii_ethtool_set_link_ksettings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffff800010bd9758-ffff800010bd97e4: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c0cf4130)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
c0cf4130-c0cf41cc: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cb9dd0)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
c000000000cb9dd0-c000000000cb9e84: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe000761782)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffe000761782-ffffffe0007617e0: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
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
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818db700)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff818db700-ffffffff818db780: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81895540)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff81895540-ffffffff818955c0: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8192c730)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff8192c730-ffffffff8192c7b0: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ethtool_convert_link_mode_to_legacy_u32(u32 *legacy_u32, const long unsigned int *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8194de00)
Location: net/core/ethtool.c:412
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff8194de00-ffffffff8194de80: ethtool_convert_link_mode_to_legacy_u32 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
