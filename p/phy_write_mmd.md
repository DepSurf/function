# Function: <code>phy_write_mmd</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8168fab0)
Location: drivers/net/phy/phy-core.c:72
Inline: True
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff8168fab0-ffffffff8168fb7b: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff816f9720)
Location: drivers/net/phy/phy-core.c:252
Inline: True
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff816f9720-ffffffff816f97f6: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736d10)
Location: drivers/net/phy/phy-core.c:296
Inline: True
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81736d10-ffffffff81736df8: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759eb0)
Location: drivers/net/phy/phy-core.c:467
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81759eb0-ffffffff81759f98: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81797180)
Location: drivers/net/phy/phy-core.c:432
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81797180-ffffffff817971dd: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817bac30)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817bac30-ffffffff817bac8d: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881960)
Location: drivers/net/phy/phy-core.c:514
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81881960-ffffffff818819c3: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890090)
Location: drivers/net/phy/phy-core.c:561
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81890090-ffffffff818900f3: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872990)
Location: drivers/net/phy/phy-core.c:561
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81872990-ffffffff818729f3: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff819030a0)
Location: drivers/net/phy/phy-core.c:562
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff819030a0-ffffffff81903103: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55b80)
Location: drivers/net/phy/phy-core.c:557
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81a55b80-ffffffff81a55bef: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf670)
Location: drivers/net/phy/phy-core.c:640
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81bdf670-ffffffff81bdf6df: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c36f60)
Location: drivers/net/phy/phy-core.c:643
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81c36f60-ffffffff81c36fcf: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cec960)
Location: drivers/net/phy/phy-core.c:641
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81cec960-ffffffff81cec9cf: phy_write_mmd (STB_GLOBAL)
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
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d3550)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffff8000109d3550-ffff8000109d35bc: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abb3f8)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
c0abb3f8-c0abb454: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a939c0)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
c000000000a939c0-c000000000a93a40: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061fcb4)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffe00061fcb4-ffffffe00061fd1a: phy_write_mmd (STB_GLOBAL)
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
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f700)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff8177f700-ffffffff8177f75d: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f4a0)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff8175f4a0-ffffffff8175f4fd: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817afab0)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817afab0-ffffffff817afb0d: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9a40)
Location: drivers/net/phy/phy-core.c:471
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817c9a40-ffffffff817c9a9d: phy_write_mmd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
