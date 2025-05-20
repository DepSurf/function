# Function: <code>linkmode_resolve_pause</code>

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
void linkmode_resolve_pause(const long unsigned int *local_adv, const long unsigned int *partner_adv, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/linkmode.c (ffffffff81886050)
Location: drivers/net/phy/linkmode.c:24
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_pause
```
**Symbols:**

```
ffffffff81886050-ffffffff818860f7: linkmode_resolve_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void linkmode_resolve_pause(const long unsigned int *local_adv, const long unsigned int *partner_adv, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/linkmode.c (ffffffff818944b0)
Location: drivers/net/phy/linkmode.c:24
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_pause
```
**Symbols:**

```
ffffffff818944b0-ffffffff81894557: linkmode_resolve_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void linkmode_resolve_pause(const long unsigned int *local_adv, const long unsigned int *partner_adv, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/linkmode.c (ffffffff81876db0)
Location: drivers/net/phy/linkmode.c:24
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_pause
```
**Symbols:**

```
ffffffff81876db0-ffffffff81876e53: linkmode_resolve_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void linkmode_resolve_pause(const long unsigned int *local_adv, const long unsigned int *partner_adv, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/linkmode.c (ffffffff819079c0)
Location: drivers/net/phy/linkmode.c:24
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_pause
```
**Symbols:**

```
ffffffff819079c0-ffffffff81907a63: linkmode_resolve_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void linkmode_resolve_pause(const long unsigned int *local_adv, const long unsigned int *partner_adv, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/linkmode.c (ffffffff81a5aa50)
Location: drivers/net/phy/linkmode.c:24
Inline: True
```
**Symbols:**

```
ffffffff81a5aa50-ffffffff81a5ab15: linkmode_resolve_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void linkmode_resolve_pause(const long unsigned int *local_adv, const long unsigned int *partner_adv, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/linkmode.c (ffffffff81be52f0)
Location: drivers/net/phy/linkmode.c:24
Inline: False
```
**Symbols:**

```
ffffffff81be52f0-ffffffff81be53b5: linkmode_resolve_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void linkmode_resolve_pause(const long unsigned int *local_adv, const long unsigned int *partner_adv, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/linkmode.c (ffffffff81c3cd80)
Location: drivers/net/phy/linkmode.c:24
Inline: False
```
**Symbols:**

```
ffffffff81c3cd80-ffffffff81c3ce45: linkmode_resolve_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void linkmode_resolve_pause(const long unsigned int *local_adv, const long unsigned int *partner_adv, bool *tx_pause, bool *rx_pause);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/linkmode.c (ffffffff81cf2180)
Location: drivers/net/phy/linkmode.c:24
Inline: False
```
**Symbols:**

```
ffffffff81cf2180-ffffffff81cf2245: linkmode_resolve_pause (STB_GLOBAL)
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
