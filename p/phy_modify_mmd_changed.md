# Function: <code>phy_modify_mmd_changed</code>

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
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817970a0)
Location: drivers/net/phy/phy-core.c:590
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffff817970a0-ffffffff81797108: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817bab50)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffff817bab50-ffffffff817babb8: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81882420)
Location: drivers/net/phy/phy-core.c:641
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81882420-ffffffff818824c9: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890b50)
Location: drivers/net/phy/phy-core.c:688
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81890b50-ffffffff81890bf9: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81873440)
Location: drivers/net/phy/phy-core.c:688
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81873440-ffffffff818734e9: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903c10)
Location: drivers/net/phy/phy-core.c:689
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81903c10-ffffffff81903cb9: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a56650)
Location: drivers/net/phy/phy-core.c:684
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81a56650-ffffffff81a56704: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81be0340)
Location: drivers/net/phy/phy-core.c:767
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81be0340-ffffffff81be03f4: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37c50)
Location: drivers/net/phy/phy-core.c:770
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffff81c37c50-ffffffff81c37d04: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cecfe0)
Location: drivers/net/phy/phy-core.c:908
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffff81cecfe0-ffffffff81ced094: phy_modify_mmd_changed (STB_GLOBAL)
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
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d3450)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffff8000109d3450-ffff8000109d34cc: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abb320)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
c0abb320-c0abb38c: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a93890)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
c000000000a93890-c000000000a93918: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061fbce)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffe00061fbce-ffffffe00061fc3c: phy_modify_mmd_changed (STB_GLOBAL)
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
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f620)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffff8177f620-ffffffff8177f688: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f3c0)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffff8175f3c0-ffffffff8175f428: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af9d0)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffff817af9d0-ffffffff817afa38: phy_modify_mmd_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_modify_mmd_changed(struct phy_device *phydev, int devad, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9960)
Location: drivers/net/phy/phy-core.c:629
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_eee_advert
```
**Symbols:**

```
ffffffff817c9960-ffffffff817c99c8: phy_modify_mmd_changed (STB_GLOBAL)
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
