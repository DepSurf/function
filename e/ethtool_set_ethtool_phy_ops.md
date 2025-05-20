# Function: <code>ethtool_set_ethtool_phy_ops</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ethtool_set_ethtool_phy_ops(const struct ethtool_phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a8ee90)
Location: net/ethtool/common.c:406
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
```
**Symbols:**

```
ffffffff81a8ee90-ffffffff81a8eeb4: ethtool_set_ethtool_phy_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ethtool_set_ethtool_phy_ops(const struct ethtool_phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a78590)
Location: net/ethtool/common.c:559
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
```
**Symbols:**

```
ffffffff81a78590-ffffffff81a785b4: ethtool_set_ethtool_phy_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ethtool_set_ethtool_phy_ops(const struct ethtool_phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81b32680)
Location: net/ethtool/common.c:573
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
```
**Symbols:**

```
ffffffff81b32680-ffffffff81b326a4: ethtool_set_ethtool_phy_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ethtool_set_ethtool_phy_ops(const struct ethtool_phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81cbdbe0)
Location: net/ethtool/common.c:577
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
```
**Symbols:**

```
ffffffff81cbdbe0-ffffffff81cbdc0a: ethtool_set_ethtool_phy_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ethtool_set_ethtool_phy_ops(const struct ethtool_phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81e7c3b0)
Location: net/ethtool/common.c:658
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
```
**Symbols:**

```
ffffffff81e7c3b0-ffffffff81e7c3da: ethtool_set_ethtool_phy_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ethtool_set_ethtool_phy_ops(const struct ethtool_phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81ed8750)
Location: net/ethtool/common.c:666
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
```
**Symbols:**

```
ffffffff81ed8750-ffffffff81ed877a: ethtool_set_ethtool_phy_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ethtool_set_ethtool_phy_ops(const struct ethtool_phy_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/common.c (0)
Location: net/ethtool/common.c:672
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
```
**Symbols:**

```
ffffffff82210a9f-ffffffff82210ab4: ethtool_set_ethtool_phy_ops.cold (STB_LOCAL)
ffffffff81f9c520-ffffffff81f9c58b: ethtool_set_ethtool_phy_ops (STB_GLOBAL)
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
