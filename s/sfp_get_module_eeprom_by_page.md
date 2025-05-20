# Function: <code>sfp_get_module_eeprom_by_page</code>

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
int sfp_get_module_eeprom_by_page(struct sfp_bus *bus, const struct ethtool_module_eeprom *page, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81878bb0)
Location: drivers/net/phy/sfp-bus.c:570
Inline: False
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81878bb0-ffffffff81878bcf: sfp_get_module_eeprom_by_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sfp_get_module_eeprom_by_page(struct sfp_bus *bus, const struct ethtool_module_eeprom *page, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff819099d0)
Location: drivers/net/phy/sfp-bus.c:575
Inline: False
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff819099d0-ffffffff819099ef: sfp_get_module_eeprom_by_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sfp_get_module_eeprom_by_page(struct sfp_bus *bus, const struct ethtool_module_eeprom *page, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d090)
Location: drivers/net/phy/sfp-bus.c:581
Inline: False
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81a5d090-ffffffff81a5d0bb: sfp_get_module_eeprom_by_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sfp_get_module_eeprom_by_page(struct sfp_bus *bus, const struct ethtool_module_eeprom *page, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81be7c90)
Location: drivers/net/phy/sfp-bus.c:530
Inline: False
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81be7c90-ffffffff81be7cbb: sfp_get_module_eeprom_by_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sfp_get_module_eeprom_by_page(struct sfp_bus *bus, const struct ethtool_module_eeprom *page, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81c40050)
Location: drivers/net/phy/sfp-bus.c:540
Inline: False
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81c40050-ffffffff81c4007b: sfp_get_module_eeprom_by_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sfp_get_module_eeprom_by_page(struct sfp_bus *bus, const struct ethtool_module_eeprom *page, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5680)
Location: drivers/net/phy/sfp-bus.c:540
Inline: False
Direct callers:
  - net/ethtool/eeprom.c:eeprom_prepare_data
```
**Symbols:**

```
ffffffff81cf5680-ffffffff81cf56ab: sfp_get_module_eeprom_by_page (STB_GLOBAL)
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
