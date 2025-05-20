# Function: <code>phy_modify_mmd</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81797110)
Location: drivers/net/phy/phy-core.c:638
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81797110-ffffffff8179717d: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817babc0)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817babc0-ffffffff817bac2d: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818824d0)
Location: drivers/net/phy/phy-core.c:689
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff818824d0-ffffffff81882579: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890c00)
Location: drivers/net/phy/phy-core.c:736
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81890c00-ffffffff81890ca9: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818734f0)
Location: drivers/net/phy/phy-core.c:736
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_loopback
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
```
**Symbols:**

```
ffffffff818734f0-ffffffff8187358f: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903cc0)
Location: drivers/net/phy/phy-core.c:737
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_loopback
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
```
**Symbols:**

```
ffffffff81903cc0-ffffffff81903d5f: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a56710)
Location: drivers/net/phy/phy-core.c:732
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_fast_retrain
  - drivers/net/phy/phy-c45.c:genphy_c45_fast_retrain
  - drivers/net/phy/phy-c45.c:genphy_c45_fast_retrain
  - drivers/net/phy/phy-c45.c:genphy_c45_fast_retrain
  - drivers/net/phy/phy-c45.c:genphy_c45_loopback
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_setup_master_slave
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
```
**Symbols:**

```
ffffffff81a56710-ffffffff81a567b9: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81be0410)
Location: drivers/net/phy/phy-core.c:815
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_loopback
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_setup_master_slave
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
```
**Symbols:**

```
ffffffff81be0410-ffffffff81be04b9: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37d20)
Location: drivers/net/phy/phy-core.c:818
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_loopback
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_setup_master_slave
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
```
**Symbols:**

```
ffffffff81c37d20-ffffffff81c37dce: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81ced0b0)
Location: drivers/net/phy/phy-core.c:956
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_loopback
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_setup_master_slave
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
```
**Symbols:**

```
ffffffff81ced0b0-ffffffff81ced15e: phy_modify_mmd (STB_GLOBAL)
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
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d34d0)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffff8000109d34d0-ffff8000109d3550: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abb38c)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
c0abb38c-c0abb3f8: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a93920)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
c000000000a93920-c000000000a939b4: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061fc3c)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffe00061fc3c-ffffffe00061fcb4: phy_modify_mmd (STB_GLOBAL)
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
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f690)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff8177f690-ffffffff8177f6fd: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f430)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff8175f430-ffffffff8175f49d: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817afa40)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817afa40-ffffffff817afaad: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_modify_mmd(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c99d0)
Location: drivers/net/phy/phy-core.c:677
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817c99d0-ffffffff817c9a3d: phy_modify_mmd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
