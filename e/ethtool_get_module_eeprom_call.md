# Function: <code>ethtool_get_module_eeprom_call</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_get_module_eeprom_call(struct net_device *dev, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a72ba0)
Location: net/ethtool/ioctl.c:2228
Inline: False
```
**Symbols:**

```
ffffffff81a72ba0-ffffffff81a72c0e: ethtool_get_module_eeprom_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethtool_get_module_eeprom_call(struct net_device *dev, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b2c660)
Location: net/ethtool/ioctl.c:2342
Inline: False
```
**Symbols:**

```
ffffffff81b2c660-ffffffff81b2c6ce: ethtool_get_module_eeprom_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_get_module_eeprom_call(struct net_device *dev, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cb7220)
Location: net/ethtool/ioctl.c:2370
Inline: False
```
**Symbols:**

```
ffffffff81cb7220-ffffffff81cb72ca: ethtool_get_module_eeprom_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_get_module_eeprom_call(struct net_device *dev, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e75490)
Location: net/ethtool/ioctl.c:2397
Inline: False
```
**Symbols:**

```
ffffffff81e75490-ffffffff81e7553a: ethtool_get_module_eeprom_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_get_module_eeprom_call(struct net_device *dev, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed1670)
Location: net/ethtool/ioctl.c:2409
Inline: False
```
**Symbols:**

```
ffffffff81ed1670-ffffffff81ed171a: ethtool_get_module_eeprom_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_get_module_eeprom_call(struct net_device *dev, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f95190)
Location: net/ethtool/ioctl.c:2458
Inline: False
Direct callers:
  - net/ethtool/eeprom.c:eeprom_fallback
```
**Symbols:**

```
ffffffff81f95190-ffffffff81f9523a: ethtool_get_module_eeprom_call (STB_GLOBAL)
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
