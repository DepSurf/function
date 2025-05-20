# Function: <code>phy_read_mmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815ec1cd)
Location: include/linux/phy.h:617
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:gen10g_read_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81649c80)
Location: include/linux/phy.h:614
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:gen10g_read_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167b190)
Location: include/linux/phy.h:649
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:gen10g_read_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8168f9f0)
Location: drivers/net/phy/phy-core.c:34
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff8168f9f0-ffffffff8168fab0: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff816f9650)
Location: drivers/net/phy/phy-core.c:214
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
**Symbols:**

```
ffffffff816f9650-ffffffff816f971b: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736c30)
Location: drivers/net/phy/phy-core.c:258
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81736c30-ffffffff81736d0a: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759dd0)
Location: drivers/net/phy/phy-core.c:429
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81759dd0-ffffffff81759eaa: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796ee0)
Location: drivers/net/phy/phy-core.c:371
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81796ee0-ffffffff81796f32: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba990)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817ba990-ffffffff817ba9e2: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818820a0)
Location: drivers/net/phy/phy-core.c:455
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
```
**Symbols:**

```
ffffffff818820a0-ffffffff818820f8: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818907d0)
Location: drivers/net/phy/phy-core.c:502
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
```
**Symbols:**

```
ffffffff818907d0-ffffffff81890828: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818730d0)
Location: drivers/net/phy/phy-core.c:502
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
```
**Symbols:**

```
ffffffff818730d0-ffffffff81873128: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff819038a0)
Location: drivers/net/phy/phy-core.c:503
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
```
**Symbols:**

```
ffffffff819038a0-ffffffff819038f8: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a562a0)
Location: drivers/net/phy/phy-core.c:498
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status
  - drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_mdix
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
```
**Symbols:**

```
ffffffff81a562a0-ffffffff81a56302: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdff30)
Location: drivers/net/phy/phy-core.c:581
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status
  - drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_mdix
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
```
**Symbols:**

```
ffffffff81bdff30-ffffffff81bdff92: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37780)
Location: drivers/net/phy/phy-core.c:584
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_status
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status
  - drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_read_mdix
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
```
**Symbols:**

```
ffffffff81c37780-ffffffff81c377e2: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cec690)
Location: drivers/net/phy/phy-core.c:596
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_status
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status
  - drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_read_mdix
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_resume
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
  - drivers/net/phy/bcm84881.c:bcm84881_aneg_done
```
**Symbols:**

```
ffffffff81cec690-ffffffff81cec6f2: phy_read_mmd (STB_GLOBAL)
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
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d31f8)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffff8000109d31f8-ffff8000109d325c: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abb174)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
c0abb174-c0abb1c8: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a935e0)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
c000000000a935e0-c000000000a93658: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f9d2)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffe00061f9d2-ffffffe00061fa30: phy_read_mmd (STB_GLOBAL)
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
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f460)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff8177f460-ffffffff8177f4b2: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175f200)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff8175f200-ffffffff8175f252: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af810)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817af810-ffffffff817af862: phy_read_mmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device *phydev, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c97a0)
Location: drivers/net/phy/phy-core.c:410
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_set_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_ethtool_get_eee
  - drivers/net/phy/phy.c:phy_get_eee_err
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
  - drivers/net/phy/phy-c45.c:genphy_c45_aneg_done
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff817c97a0-ffffffff817c97f2: phy_read_mmd (STB_GLOBAL)
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
