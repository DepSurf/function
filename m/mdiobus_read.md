# Function: <code>mdiobus_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff815ecfd0)
Location: drivers/net/phy/mdio_bus.c:411
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff815ecfd0-ffffffff815ed026: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8164bc50)
Location: drivers/net/phy/mdio_bus.c:478
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff8164bc50-ffffffff8164bca6: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8167d3f0)
Location: drivers/net/phy/mdio_bus.c:483
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:gen10g_read_status
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff8167d3f0-ffffffff8167d4bf: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff816927c0)
Location: drivers/net/phy/mdio_bus.c:534
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff816927c0-ffffffff81692891: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff816fc300)
Location: drivers/net/phy/mdio_bus.c:535
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff816fc300-ffffffff816fc3d9: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81739dc0)
Location: drivers/net/phy/mdio_bus.c:617
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff81739dc0-ffffffff81739e18: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8175d220)
Location: drivers/net/phy/mdio_bus.c:616
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff8175d220-ffffffff8175d278: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8179a7b0)
Location: drivers/net/phy/mdio_bus.c:633
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff8179a7b0-ffffffff8179a80c: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817be270)
Location: drivers/net/phy/mdio_bus.c:625
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff817be270-ffffffff817be2cc: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81886ec0)
Location: drivers/net/phy/mdio_bus.c:906
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status_fixed
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81886ec0-ffffffff81886f32: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff818951e0)
Location: drivers/net/phy/mdio_bus.c:847
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status_fixed
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
**Symbols:**

```
ffffffff818951e0-ffffffff8189522f: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81877d90)
Location: drivers/net/phy/mdio_bus.c:846
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status_fixed
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
**Symbols:**

```
ffffffff81877d90-ffffffff81877ddf: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81908b60)
Location: drivers/net/phy/mdio_bus.c:857
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status_fixed
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
**Symbols:**

```
ffffffff81908b60-ffffffff81908baf: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81a5b620)
Location: drivers/net/phy/mdio_bus.c:864
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status_fixed
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_read_master_slave
  - drivers/net/phy/phy_device.c:genphy_read_master_slave
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
**Symbols:**

```
ffffffff81a5b620-ffffffff81a5b675: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81be6a50)
Location: drivers/net/phy/mdio_bus.c:869
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status_fixed
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_read_master_slave
  - drivers/net/phy/phy_device.c:genphy_read_master_slave
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
**Symbols:**

```
ffffffff81be6a50-ffffffff81be6aa5: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3e8c0)
Location: drivers/net/phy/mdio_bus.c:1049
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status_fixed
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_read_master_slave
  - drivers/net/phy/phy_device.c:genphy_read_master_slave
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81c3e8c0-ffffffff81c3e915: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf3e10)
Location: drivers/net/phy/mdio_bus.c:1067
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_status_fixed
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:genphy_read_master_slave
  - drivers/net/phy/phy_device.c:genphy_read_master_slave
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81cf3e10-ffffffff81cf3e65: mdiobus_read (STB_GLOBAL)
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
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffff8000109d79a8)
Location: drivers/net/phy/mdio_bus.c:625
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_restart_autoneg
```
**Symbols:**

```
ffff8000109d79a8-ffff8000109d7a1c: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c0abf430)
Location: drivers/net/phy/mdio_bus.c:625
Inline: True
Direct callers:
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
c0abf430-c0abf4a8: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c000000000a99990)
Location: drivers/net/phy/mdio_bus.c:625
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
c000000000a99990-c000000000a99a1c: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffe00062397a)
Location: drivers/net/phy/mdio_bus.c:625
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffe00062397a-ffffffe0006239e8: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81782d40)
Location: drivers/net/phy/mdio_bus.c:625
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff81782d40-ffffffff81782d9c: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81762ad0)
Location: drivers/net/phy/mdio_bus.c:625
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff81762ad0-ffffffff81762b2c: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817b30f0)
Location: drivers/net/phy/mdio_bus.c:625
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff817b30f0-ffffffff817b314c: mdiobus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_read(struct mii_bus *bus, int addr, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817cd0a0)
Location: drivers/net/phy/mdio_bus.c:625
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_update_link
  - drivers/net/phy/phy_device.c:genphy_aneg_done
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
  - drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg
```
**Symbols:**

```
ffffffff817cd0a0-ffffffff817cd0fc: mdiobus_read (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
