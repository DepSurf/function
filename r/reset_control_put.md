# Function: <code>reset_control_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff814df480)
Location: drivers/reset/core.c:236
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff814df480-ffffffff814df4ae: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815304e0)
Location: drivers/reset/core.c:324
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff815304e0-ffffffff81530557: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8155cca0)
Location: drivers/reset/core.c:365
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff8155cca0-ffffffff8155cd17: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8157171d)
Location: drivers/reset/core.c:411
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff81571750-ffffffff81571790: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d5bf0)
Location: drivers/reset/core.c:521
Inline: True
Direct callers:
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff815d5bf0-ffffffff815d5c90: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160ec80)
Location: drivers/reset/core.c:615
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff8160ec80-ffffffff8160ed1e: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b860)
Location: drivers/reset/core.c:616
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff8162b860-ffffffff8162b8fe: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8165f660)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff8165f660-ffffffff8165f6f9: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681dc0)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81681dc0-ffffffff81681e74: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732df0)
Location: drivers/reset/core.c:758
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81732df0-ffffffff81732ea9: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174efb0)
Location: drivers/reset/core.c:832
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff8174efb0-ffffffff8174f069: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732ec0)
Location: drivers/reset/core.c:995
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81732ec0-ffffffff8173304a: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff817b3c60)
Location: drivers/reset/core.c:995
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81cf86d8-ffffffff81cf86ec: reset_control_put.cold (STB_LOCAL)
ffffffff817b3c20-ffffffff817b3db4: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff818ef320)
Location: drivers/reset/core.c:996
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81ec0752-ffffffff81ec0766: reset_control_put.cold (STB_LOCAL)
ffffffff818ef2e0-ffffffff818ef49c: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff81a47010)
Location: drivers/reset/core.c:996
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff82094eb8-ffffffff82094ecc: reset_control_put.cold (STB_LOCAL)
ffffffff81a46fd0-ffffffff81a4718c: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff81a911b0)
Location: drivers/reset/core.c:996
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff82115cdd-ffffffff82115cf1: reset_control_put.cold (STB_LOCAL)
ffffffff81a91170-ffffffff81a9132c: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae399d)
Location: drivers/reset/core.c:999
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff821f39e3-ffffffff821f39f8: reset_control_put.cold (STB_LOCAL)
ffffffff81ae3960-ffffffff81ae3a19: reset_control_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084cb78)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffff80001084cb78-ffff80001084cc2c: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958fd8)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8_smp_boot_secondary
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/soc/tegra/pmc.c:tegra_powergate_init
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
c0958fd8-c095907c: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008eb200)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
c0000000008eb200-c0000000008eb31c: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052c34a)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffe00052c34a-ffffffe00052c436: reset_control_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81647840)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81647840-ffffffff816478f4: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627ca0)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81627ca0-ffffffff81627d54: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81675c00)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81675c00-ffffffff81675cb4: reset_control_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void reset_control_put(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81690260)
Location: drivers/reset/core.c:757
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:devm_reset_control_release
  - drivers/net/phy/mdio_bus.c:mdiobus_unregister_device
```
**Symbols:**

```
ffffffff81690260-ffffffff81690314: reset_control_put (STB_GLOBAL)
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
