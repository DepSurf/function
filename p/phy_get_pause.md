# Function: <code>phy_get_pause</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void phy_get_pause(struct phy_device *phydev, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81883800)
Location: drivers/net/phy/phy_device.c:2653
Inline: False
```
**Symbols:**

```
ffffffff81883800-ffffffff81883837: phy_get_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void phy_get_pause(struct phy_device *phydev, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81891f50)
Location: drivers/net/phy/phy_device.c:2703
Inline: False
```
**Symbols:**

```
ffffffff81891f50-ffffffff81891f87: phy_get_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void phy_get_pause(struct phy_device *phydev, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81874590)
Location: drivers/net/phy/phy_device.c:2749
Inline: False
```
**Symbols:**

```
ffffffff81874590-ffffffff818745c7: phy_get_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void phy_get_pause(struct phy_device *phydev, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81904f70)
Location: drivers/net/phy/phy_device.c:2795
Inline: False
```
**Symbols:**

```
ffffffff81904f70-ffffffff81904fa7: phy_get_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void phy_get_pause(struct phy_device *phydev, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a58550)
Location: drivers/net/phy/phy_device.c:2823
Inline: True
```
**Symbols:**

```
ffffffff81a58550-ffffffff81a585a3: phy_get_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void phy_get_pause(struct phy_device *phydev, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be23f0)
Location: drivers/net/phy/phy_device.c:2829
Inline: True
```
**Symbols:**

```
ffffffff81be23f0-ffffffff81be2443: phy_get_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void phy_get_pause(struct phy_device *phydev, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c39cc0)
Location: drivers/net/phy/phy_device.c:2876
Inline: True
```
**Symbols:**

```
ffffffff81c39cc0-ffffffff81c39d13: phy_get_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void phy_get_pause(struct phy_device *phydev, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cef040)
Location: drivers/net/phy/phy_device.c:2883
Inline: True
```
**Symbols:**

```
ffffffff81cef040-ffffffff81cef093: phy_get_pause (STB_GLOBAL)
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
