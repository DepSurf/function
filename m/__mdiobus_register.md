# Function: <code>__mdiobus_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff815eca50)
Location: drivers/net/phy/mdio_bus.c:250
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff815eca50-ffffffff815ecbe1: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8164b910)
Location: drivers/net/phy/mdio_bus.c:301
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff8164b910-ffffffff8164baa6: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff8167d120)
Location: drivers/net/phy/mdio_bus.c:304
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff8167d120-ffffffff8167d2b0: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81692140)
Location: drivers/net/phy/mdio_bus.c:328
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81692140-ffffffff8169236a: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff816fbf30)
Location: drivers/net/phy/mdio_bus.c:329
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff816fbf30-ffffffff816fc16b: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:361
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81739e18-ffffffff81739e3a: __mdiobus_register.cold.14 (STB_LOCAL)
ffffffff817395d0-ffffffff81739822: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:360
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff8175d531-ffffffff8175d54b: __mdiobus_register.cold.15 (STB_LOCAL)
ffffffff8175ccf0-ffffffff8175cf4a: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:377
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff8179aad9-ffffffff8179ab15: __mdiobus_register.cold (STB_LOCAL)
ffffffff8179a170-ffffffff8179a394: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff817be583-ffffffff817be5bf: __mdiobus_register.cold (STB_LOCAL)
ffffffff817bdc70-ffffffff817bde94: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:591
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff8188730e-ffffffff8188734c: __mdiobus_register.cold (STB_LOCAL)
ffffffff81886f40-ffffffff818871c8: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:518
Inline: False
Direct callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81c194b6-ffffffff81c194d0: __mdiobus_register.cold (STB_LOCAL)
ffffffff81895320-ffffffff81895653: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:518
Inline: False
Direct callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81c0b309-ffffffff81c0b323: __mdiobus_register.cold (STB_LOCAL)
ffffffff81877940-ffffffff81877c66: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:518
Inline: False
Direct callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81d1070e-ffffffff81d10728: __mdiobus_register.cold (STB_LOCAL)
ffffffff81908690-ffffffff81908a1f: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:523
Inline: False
Direct callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81edb49f-ffffffff81edb4b9: __mdiobus_register.cold (STB_LOCAL)
ffffffff81a5b9d0-ffffffff81a5bd61: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81be6450)
Location: drivers/net/phy/mdio_bus.c:528
Inline: False
Direct callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/net/mdio/acpi_mdio.c:acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81be6450-ffffffff81be6800: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81c3dc10)
Location: drivers/net/phy/mdio_bus.c:650
Inline: False
Direct callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81c3dc10-ffffffff81c3e0c1: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff81cf3100)
Location: drivers/net/phy/mdio_bus.c:659
Inline: False
Direct callers:
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
  - drivers/net/mdio/acpi_mdio.c:__acpi_mdiobus_register
```
**Symbols:**

```
ffffffff81cf3100-ffffffff81cf35dc: __mdiobus_register (STB_GLOBAL)
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
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffff8000109d7348)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffff8000109d7348-ffff8000109d7580: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c0abeae8)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
c0abeae8-c0abed24: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (c000000000a98d90)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
c000000000a98d90-c000000000a990f0: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffe000623118)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffe000623118-ffffffe000623324: __mdiobus_register (STB_GLOBAL)
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
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81783053-ffffffff8178308f: __mdiobus_register.cold (STB_LOCAL)
ffffffff81782740-ffffffff81782964: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff81762de3-ffffffff81762e1f: __mdiobus_register.cold (STB_LOCAL)
ffffffff817624d0-ffffffff817626f4: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff817b3403-ffffffff817b343f: __mdiobus_register.cold (STB_LOCAL)
ffffffff817b2af0-ffffffff817b2d14: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __mdiobus_register(struct mii_bus *bus, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_bus.c (0)
Location: drivers/net/phy/mdio_bus.c:369
Inline: False
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_init
```
**Symbols:**

```
ffffffff817cd3d3-ffffffff817cd40f: __mdiobus_register.cold (STB_LOCAL)
ffffffff817cca80-ffffffff817ccca4: __mdiobus_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
