# Function: <code>ethtool_get_module_info_call</code>

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
int ethtool_get_module_info_call(struct net_device *dev, struct ethtool_modinfo *modinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a76b20)
Location: net/ethtool/ioctl.c:2191
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a76b20-ffffffff81a76b8e: ethtool_get_module_info_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethtool_get_module_info_call(struct net_device *dev, struct ethtool_modinfo *modinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b30cf0)
Location: net/ethtool/ioctl.c:2305
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81b30cf0-ffffffff81b30d5e: ethtool_get_module_info_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_get_module_info_call(struct net_device *dev, struct ethtool_modinfo *modinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cbbc20)
Location: net/ethtool/ioctl.c:2333
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81cbbc20-ffffffff81cbbcbe: ethtool_get_module_info_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_get_module_info_call(struct net_device *dev, struct ethtool_modinfo *modinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e7a200)
Location: net/ethtool/ioctl.c:2360
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81e7a200-ffffffff81e7a29e: ethtool_get_module_info_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_get_module_info_call(struct net_device *dev, struct ethtool_modinfo *modinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed6500)
Location: net/ethtool/ioctl.c:2372
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81ed6500-ffffffff81ed659e: ethtool_get_module_info_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_get_module_info_call(struct net_device *dev, struct ethtool_modinfo *modinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f9a080)
Location: net/ethtool/ioctl.c:2421
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/eeprom.c:eeprom_fallback
```
**Symbols:**

```
ffffffff81f9a080-ffffffff81f9a11e: ethtool_get_module_info_call (STB_GLOBAL)
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
