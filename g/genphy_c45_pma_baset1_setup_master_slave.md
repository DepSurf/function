# Function: <code>genphy_c45_pma_baset1_setup_master_slave</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int genphy_c45_pma_baset1_setup_master_slave(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy-c45.c (0)
Location: drivers/net/phy/phy-c45.c:78
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81edaf5f-ffffffff81edaf75: genphy_c45_pma_baset1_setup_master_slave.cold (STB_LOCAL)
ffffffff81a547a0-ffffffff81a54800: genphy_c45_pma_baset1_setup_master_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genphy_c45_pma_baset1_setup_master_slave(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81bddce0)
Location: drivers/net/phy/phy-c45.c:78
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81bddce0-ffffffff81bddd67: genphy_c45_pma_baset1_setup_master_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genphy_c45_pma_baset1_setup_master_slave(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81c34bf0)
Location: drivers/net/phy/phy-c45.c:80
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81c34bf0-ffffffff81c34c77: genphy_c45_pma_baset1_setup_master_slave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genphy_c45_pma_baset1_setup_master_slave(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81ce9af0)
Location: drivers/net/phy/phy-c45.c:80
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced
```
**Symbols:**

```
ffffffff81ce9af0-ffffffff81ce9b77: genphy_c45_pma_baset1_setup_master_slave (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
