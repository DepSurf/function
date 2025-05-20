# Function: <code>mdiobus_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff815ed0a0)
Location: drivers/net/phy/mdio_bus.c:464
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_setup_forced
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_soft_reset
```
**Symbols:**

```
ffffffff815ed0a0-ffffffff815ed101: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8164bd20)
Location: drivers/net/phy/mdio_bus.c:531
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff8164bd20-ffffffff8164bd81: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8167d6a0)
Location: drivers/net/phy/mdio_bus.c:540
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff8167d6a0-ffffffff8167d776: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff816926e0)
Location: drivers/net/phy/mdio_bus.c:591
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff816926e0-ffffffff816927b8: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff816fc5d0)
Location: drivers/net/phy/mdio_bus.c:592
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_aneg
  - drivers/net/phy/phy_device.c:genphy_restart_aneg
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff816fc5d0-ffffffff816fc6af: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81739b10)
Location: drivers/net/phy/mdio_bus.c:670
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:genphy_soft_reset
```
**Symbols:**

```
ffffffff81739b10-ffffffff81739b71: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8175d4d0)
Location: drivers/net/phy/mdio_bus.c:669
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff8175d4d0-ffffffff8175d531: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8179aa60)
Location: drivers/net/phy/mdio_bus.c:686
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff8179aa60-ffffffff8179aac3: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817be520)
Location: drivers/net/phy/mdio_bus.c:678
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff817be520-ffffffff817be583: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81886c60)
Location: drivers/net/phy/mdio_bus.c:961
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81886c60-ffffffff81886cda: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81894fd0)
Location: drivers/net/phy/mdio_bus.c:896
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81894fd0-ffffffff81895026: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81877880)
Location: drivers/net/phy/mdio_bus.c:895
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81877880-ffffffff818778d6: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff819085d0)
Location: drivers/net/phy/mdio_bus.c:906
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff819085d0-ffffffff81908626: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81a5bfc0)
Location: drivers/net/phy/mdio_bus.c:913
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81a5bfc0-ffffffff81a5c020: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81be6370)
Location: drivers/net/phy/mdio_bus.c:918
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81be6370-ffffffff81be63d0: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3e580)
Location: drivers/net/phy/mdio_bus.c:1148
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81c3e580-ffffffff81c3e5e0: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf3ad0)
Location: drivers/net/phy/mdio_bus.c:1166
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81cf3ad0-ffffffff81cf3b30: mdiobus_write (STB_GLOBAL)
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
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffff8000109d7bc0)
Location: drivers/net/phy/mdio_bus.c:678
Inline: True
Direct callers:
  - drivers/phy/broadcom/phy-bcm-ns2-pcie.c:ns2_pci_phy_init
  - drivers/phy/broadcom/phy-bcm-ns2-pcie.c:ns2_pci_phy_init
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_restart_autoneg
```
**Symbols:**

```
ffff8000109d7bc0-ffff8000109d7c44: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c0abf0ac)
Location: drivers/net/phy/mdio_bus.c:678
Inline: True
Direct callers:
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
c0abf0ac-c0abf12c: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c000000000a993b0)
Location: drivers/net/phy/mdio_bus.c:678
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
c000000000a993b0-c000000000a99444: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffe000623672)
Location: drivers/net/phy/mdio_bus.c:678
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffe000623672-ffffffe0006236e8: mdiobus_write (STB_GLOBAL)
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
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81782ff0)
Location: drivers/net/phy/mdio_bus.c:678
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81782ff0-ffffffff81783053: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81762d80)
Location: drivers/net/phy/mdio_bus.c:678
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff81762d80-ffffffff81762de3: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817b33a0)
Location: drivers/net/phy/mdio_bus.c:678
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff817b33a0-ffffffff817b3403: mdiobus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_write(struct mii_bus *bus, int addr, u32 regnum, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff817cd370)
Location: drivers/net/phy/mdio_bus.c:678
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
**Symbols:**

```
ffffffff817cd370-ffffffff817cd3d3: mdiobus_write (STB_GLOBAL)
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
