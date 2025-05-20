# Function: <code>fwnode_mdio_find_device</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct mdio_device *fwnode_mdio_find_device(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81906575)
Location: drivers/net/phy/phy_device.c:2920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
**Symbols:**

```
ffffffff81904a10-ffffffff81904a3b: fwnode_mdio_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct mdio_device *fwnode_mdio_find_device(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a59365)
Location: drivers/net/phy/phy_device.c:2948
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
**Symbols:**

```
ffffffff81a578c0-ffffffff81a57903: fwnode_mdio_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mdio_device *fwnode_mdio_find_device(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be30f5)
Location: drivers/net/phy/phy_device.c:2954
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
**Symbols:**

```
ffffffff81be1730-ffffffff81be1773: fwnode_mdio_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mdio_device *fwnode_mdio_find_device(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3aff5)
Location: drivers/net/phy/phy_device.c:3110
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
**Symbols:**

```
ffffffff81c38fc0-ffffffff81c39003: fwnode_mdio_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mdio_device *fwnode_mdio_find_device(struct fwnode_handle *fwnode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cefc25)
Location: drivers/net/phy/phy_device.c:3185
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
**Symbols:**

```
ffffffff81cee350-ffffffff81cee393: fwnode_mdio_find_device (STB_GLOBAL)
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
