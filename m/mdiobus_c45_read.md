# Function: <code>mdiobus_c45_read</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81882cb5)
Location: include/linux/mdio.h:354
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81893453)
Location: include/linux/mdio.h:355
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81876034)
Location: include/linux/mdio.h:368
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81906bb4)
Location: include/linux/mdio.h:371
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a52c46)
Location: include/linux/mdio.h:479
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy_device.c (ffffffff81a59aa4)
Location: include/linux/mdio.h:479
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdcd96)
Location: include/linux/mdio.h:479
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy_device.c (ffffffff81be38c4)
Location: include/linux/mdio.h:479
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_c45_read(struct mii_bus *bus, int addr, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3e2a0)
Location: drivers/net/phy/mdio_bus.c:1072
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
**Symbols:**

```
ffffffff81c3e2a0-ffffffff81c3e301: mdiobus_c45_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mdiobus_c45_read(struct mii_bus *bus, int addr, int devad, u32 regnum);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf42a0)
Location: drivers/net/phy/mdio_bus.c:1090
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
**Symbols:**

```
ffffffff81cf42a0-ffffffff81cf4301: mdiobus_c45_read (STB_GLOBAL)
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
