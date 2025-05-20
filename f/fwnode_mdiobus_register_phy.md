# Function: <code>fwnode_mdiobus_register_phy</code>

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
int fwnode_mdiobus_register_phy(struct mii_bus *bus, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (ffffffff8190b940)
Location: drivers/net/mdio/fwnode_mdio.c:85
Inline: False
```
**Symbols:**

```
ffffffff8190b940-ffffffff8190bac8: fwnode_mdiobus_register_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fwnode_mdiobus_register_phy(struct mii_bus *bus, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81a5f260)
Location: drivers/net/mdio/fwnode_mdio.c:90
Inline: False
Direct callers:
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81a5f260-ffffffff81a5f3fa: fwnode_mdiobus_register_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fwnode_mdiobus_register_phy(struct mii_bus *bus, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81bea600)
Location: drivers/net/mdio/fwnode_mdio.c:112
Inline: False
Direct callers:
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81bea600-ffffffff81bea7bf: fwnode_mdiobus_register_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fwnode_mdiobus_register_phy(struct mii_bus *bus, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81c42a30)
Location: drivers/net/mdio/fwnode_mdio.c:112
Inline: False
Direct callers:
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81c42a30-ffffffff81c42bf8: fwnode_mdiobus_register_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fwnode_mdiobus_register_phy(struct mii_bus *bus, struct fwnode_handle *child, u32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/mdio/fwnode_mdio.c (ffffffff81cf80f0)
Location: drivers/net/mdio/fwnode_mdio.c:113
Inline: False
Direct callers:
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81cf80f0-ffffffff81cf82b8: fwnode_mdiobus_register_phy (STB_GLOBAL)
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
