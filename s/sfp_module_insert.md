# Function: <code>sfp_module_insert</code>

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
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8173a990)
Location: drivers/net/phy/sfp-bus.c:552
Inline: False
```
**Symbols:**

```
ffffffff8173a990-ffffffff8173a9c1: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8175e0c0)
Location: drivers/net/phy/sfp-bus.c:554
Inline: False
```
**Symbols:**

```
ffffffff8175e0c0-ffffffff8175e0f1: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8179b740)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
ffffffff8179b740-ffffffff8179b772: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817bf1f0)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
ffffffff817bf1f0-ffffffff817bf222: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff818888d0)
Location: drivers/net/phy/sfp-bus.c:722
Inline: False
```
**Symbols:**

```
ffffffff818888d0-ffffffff81888928: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81896b60)
Location: drivers/net/phy/sfp-bus.c:736
Inline: False
```
**Symbols:**

```
ffffffff81896b60-ffffffff81896bb8: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81878f60)
Location: drivers/net/phy/sfp-bus.c:773
Inline: False
```
**Symbols:**

```
ffffffff81878f60-ffffffff81879063: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:783
Inline: False
```
**Symbols:**

```
ffffffff81d10793-ffffffff81d107a8: sfp_module_insert.cold (STB_LOCAL)
ffffffff81909af0-ffffffff81909c06: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:789
Inline: False
```
**Symbols:**

```
ffffffff81edb539-ffffffff81edb54e: sfp_module_insert.cold (STB_LOCAL)
ffffffff81a5d1e0-ffffffff81a5d2ea: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id, const struct sfp_quirk *quirk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:738
Inline: False
```
**Symbols:**

```
ffffffff8209d63b-ffffffff8209d658: sfp_module_insert.cold (STB_LOCAL)
ffffffff81be8e80-ffffffff81be8eff: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id, const struct sfp_quirk *quirk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:768
Inline: False
```
**Symbols:**

```
ffffffff8211e545-ffffffff8211e562: sfp_module_insert.cold (STB_LOCAL)
ffffffff81c412b0-ffffffff81c4132f: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id, const struct sfp_quirk *quirk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:768
Inline: False
```
**Symbols:**

```
ffffffff821ffb98-ffffffff821ffbb5: sfp_module_insert.cold (STB_LOCAL)
ffffffff81cf6920-ffffffff81cf699f: sfp_module_insert (STB_GLOBAL)
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
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffff8000109d9560)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
ffff8000109d9560-ffff8000109d95c8: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c0ac015c)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
c0ac015c-c0ac01a8: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c000000000a9afd0)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
c000000000a9afd0-c000000000a9b048: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffe000624584)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
ffffffe000624584-ffffffe0006245c2: sfp_module_insert (STB_GLOBAL)
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
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81783cc0)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
ffffffff81783cc0-ffffffff81783cf2: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81763610)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
ffffffff81763610-ffffffff81763642: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817b4070)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
ffffffff817b4070-ffffffff817b40a2: sfp_module_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sfp_module_insert(struct sfp_bus *bus, const struct sfp_eeprom_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817ce040)
Location: drivers/net/phy/sfp-bus.c:551
Inline: False
```
**Symbols:**

```
ffffffff817ce040-ffffffff817ce072: sfp_module_insert (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sfp_quirk *quirk</code>
</li>
</ul>
</details>
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
