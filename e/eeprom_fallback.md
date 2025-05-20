# Function: <code>eeprom_fallback</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/eeprom.c (ffffffff81a81dd0)
Location: net/ethtool/eeprom.c:53
Inline: True
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81a81dd0-ffffffff81a81ef3: eeprom_fallback.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/eeprom.c (ffffffff81b3ba00)
Location: net/ethtool/eeprom.c:53
Inline: True
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81b3ba00-ffffffff81b3bb23: eeprom_fallback.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/eeprom.c (ffffffff81cc7a40)
Location: net/ethtool/eeprom.c:53
Inline: True
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81cc7a40-ffffffff81cc7b83: eeprom_fallback.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/eeprom.c (ffffffff81e87100)
Location: net/ethtool/eeprom.c:53
Inline: True
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81e87100-ffffffff81e87243: eeprom_fallback.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/eeprom.c (ffffffff81ee3b60)
Location: net/ethtool/eeprom.c:53
Inline: True
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81ee3b60-ffffffff81ee3ca3: eeprom_fallback.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int eeprom_fallback(struct eeprom_req_info *request, struct eeprom_reply_data *reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/eeprom.c (ffffffff81fa7940)
Location: net/ethtool/eeprom.c:53
Inline: False
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81fa7940-ffffffff81fa7a83: eeprom_fallback (STB_LOCAL)
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
</ul>
