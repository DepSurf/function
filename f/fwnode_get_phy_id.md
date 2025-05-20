# Function: <code>fwnode_get_phy_id</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int fwnode_get_phy_id(struct fwnode_handle *fwnode, u32 *phy_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81904550)
Location: drivers/net/phy/phy_device.c:840
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff81904550-ffffffff819045de: fwnode_get_phy_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fwnode_get_phy_id(struct fwnode_handle *fwnode, u32 *phy_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a57210)
Location: drivers/net/phy/phy_device.c:871
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff81a57210-ffffffff81a572bf: fwnode_get_phy_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fwnode_get_phy_id(struct fwnode_handle *fwnode, u32 *phy_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be10b0)
Location: drivers/net/phy/phy_device.c:875
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff81be10b0-ffffffff81be115f: fwnode_get_phy_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fwnode_get_phy_id(struct fwnode_handle *fwnode, u32 *phy_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c389c0)
Location: drivers/net/phy/phy_device.c:906
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff81c389c0-ffffffff81c38a6f: fwnode_get_phy_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fwnode_get_phy_id(struct fwnode_handle *fwnode, u32 *phy_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cedd50)
Location: drivers/net/phy/phy_device.c:909
Inline: False
Direct callers:
  - drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy
```
**Symbols:**

```
ffffffff81cedd50-ffffffff81ceddff: fwnode_get_phy_id (STB_GLOBAL)
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
