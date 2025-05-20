# Function: <code>sfp_get_module_eeprom</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8173a820)
Location: drivers/net/phy/sfp-bus.c:396
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff8173a820-ffffffff8173a83f: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8175df50)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff8175df50-ffffffff8175df6f: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8179b5d0)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff8179b5d0-ffffffff8179b5ef: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817bf080)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff817bf080-ffffffff817bf09f: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81888080)
Location: drivers/net/phy/sfp-bus.c:520
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff81888080-ffffffff8188809f: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81896320)
Location: drivers/net/phy/sfp-bus.c:534
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff81896320-ffffffff8189633f: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81878b90)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_module_eeprom_call
```
**Symbols:**

```
ffffffff81878b90-ffffffff81878baf: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff819099b0)
Location: drivers/net/phy/sfp-bus.c:556
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_module_eeprom_call
```
**Symbols:**

```
ffffffff819099b0-ffffffff819099cf: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d060)
Location: drivers/net/phy/sfp-bus.c:562
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_module_eeprom_call
```
**Symbols:**

```
ffffffff81a5d060-ffffffff81a5d08b: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81be7c50)
Location: drivers/net/phy/sfp-bus.c:511
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_module_eeprom_call
```
**Symbols:**

```
ffffffff81be7c50-ffffffff81be7c7b: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81c40010)
Location: drivers/net/phy/sfp-bus.c:521
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_module_eeprom_call
```
**Symbols:**

```
ffffffff81c40010-ffffffff81c4003b: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5640)
Location: drivers/net/phy/sfp-bus.c:521
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_module_eeprom_call
```
**Symbols:**

```
ffffffff81cf5640-ffffffff81cf566b: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffff8000109d9308)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffff8000109d9308-ffff8000109d9354: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c0abff80)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
c0abff80-c0abffa8: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c000000000a9aca0)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
c000000000a9aca0-c000000000a9ace8: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffe00062440a)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffe00062440a-ffffffe000624442: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81783b50)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff81783b50-ffffffff81783b6f: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817634a0)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff817634a0-ffffffff817634bf: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817b3f00)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff817b3f00-ffffffff817b3f1f: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sfp_get_module_eeprom(struct sfp_bus *bus, struct ethtool_eeprom *ee, u8 *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817cded0)
Location: drivers/net/phy/sfp-bus.c:400
Inline: False
Direct callers:
  - net/core/ethtool.c:__ethtool_get_module_eeprom
```
**Symbols:**

```
ffffffff817cded0-ffffffff817cdeef: sfp_get_module_eeprom (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
