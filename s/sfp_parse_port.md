# Function: <code>sfp_parse_port</code>

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
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8173aa00)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff8173aa00-ffffffff8173aa6e: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8175e130)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff8175e130-ffffffff8175e1ce: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff8179befe-ffffffff8179bf1c: sfp_parse_port.cold (STB_LOCAL)
ffffffff8179b7b0-ffffffff8179b84e: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff817bf9ae-ffffffff817bf9cc: sfp_parse_port.cold (STB_LOCAL)
ffffffff817bf260-ffffffff817bf2fe: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:121
Inline: False
```
**Symbols:**

```
ffffffff81888ed6-ffffffff81888ef4: sfp_parse_port.cold (STB_LOCAL)
ffffffff81888290-ffffffff81888341: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:136
Inline: False
```
**Symbols:**

```
ffffffff81c1951c-ffffffff81c1953a: sfp_parse_port.cold (STB_LOCAL)
ffffffff81896530-ffffffff818965e1: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:136
Inline: False
```
**Symbols:**

```
ffffffff81c0b370-ffffffff81c0b38e: sfp_parse_port.cold (STB_LOCAL)
ffffffff81878dc0-ffffffff81878e5a: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:136
Inline: False
```
**Symbols:**

```
ffffffff81d10775-ffffffff81d10793: sfp_parse_port.cold (STB_LOCAL)
ffffffff819099f0-ffffffff81909a8a: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:142
Inline: False
```
**Symbols:**

```
ffffffff81edb50f-ffffffff81edb539: sfp_parse_port.cold (STB_LOCAL)
ffffffff81a5d0c0-ffffffff81a5d16b: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81be7cd0)
Location: drivers/net/phy/sfp-bus.c:49
Inline: False
```
**Symbols:**

```
ffffffff81be7cd0-ffffffff81be7d9a: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81c40090)
Location: drivers/net/phy/sfp-bus.c:49
Inline: False
```
**Symbols:**

```
ffffffff81c40090-ffffffff81c4013a: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81cf56c0)
Location: drivers/net/phy/sfp-bus.c:49
Inline: False
```
**Symbols:**

```
ffffffff81cf56c0-ffffffff81cf576a: sfp_parse_port (STB_GLOBAL)
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
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffff8000109d9620)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffff8000109d9620-ffff8000109d9744: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c0ac01ec)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
c0ac01ec-c0ac0324: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c000000000a9b0c0)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
c000000000a9b0c0-c000000000a9b250: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffe0006245f4)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffe0006245f4-ffffffe0006246a2: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff8178447e-ffffffff8178449c: sfp_parse_port.cold (STB_LOCAL)
ffffffff81783d30-ffffffff81783dce: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff81763dce-ffffffff81763dec: sfp_parse_port.cold (STB_LOCAL)
ffffffff81763680-ffffffff8176371e: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff817b482e-ffffffff817b484c: sfp_parse_port.cold (STB_LOCAL)
ffffffff817b40e0-ffffffff817b417e: sfp_parse_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sfp_parse_port(struct sfp_bus *bus, const struct sfp_eeprom_id *id, long unsigned int *support);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff817ce7fe-ffffffff817ce81c: sfp_parse_port.cold (STB_LOCAL)
ffffffff817ce0b0-ffffffff817ce14e: sfp_parse_port (STB_GLOBAL)
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
