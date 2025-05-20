# Function: <code>i2c_acpi_find_bus_speed</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81709e80)
Location: drivers/i2c/i2c-core.c:317
Inline: False
```
**Symbols:**

```
ffffffff81709e80-ffffffff81709f7f: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817240e0)
Location: drivers/i2c/i2c-core-acpi.c:273
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817240e0-ffffffff817241cd: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795850)
Location: drivers/i2c/i2c-core-acpi.c:273
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81795850-ffffffff81795933: i2c_acpi_find_bus_speed.part.5 (STB_LOCAL)
ffffffff81795940-ffffffff8179596e: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8310)
Location: drivers/i2c/i2c-core-acpi.c:273
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817d8310-ffffffff817d83f0: i2c_acpi_find_bus_speed.part.5 (STB_LOCAL)
ffffffff817d83f0-ffffffff817d841e: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff340)
Location: drivers/i2c/i2c-core-acpi.c:296
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817ff340-ffffffff817ff421: i2c_acpi_find_bus_speed.part.3 (STB_LOCAL)
ffffffff817ff430-ffffffff817ff45e: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81840660)
Location: drivers/i2c/i2c-core-acpi.c:318
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81840580-ffffffff81840656: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffffffff81841101-ffffffff81841117: i2c_acpi_find_bus_speed.part.0.cold (STB_LOCAL)
ffffffff81840660-ffffffff81840690: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81872030)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81871f40-ffffffff81872029: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffffffff81872a61-ffffffff81872a90: i2c_acpi_find_bus_speed.part.0.cold (STB_LOCAL)
ffffffff81872030-ffffffff81872060: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81946030)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed
```
**Symbols:**

```
ffffffff81945f40-ffffffff81946029: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffffffff81946bef-ffffffff81946c1e: i2c_acpi_find_bus_speed.part.0.cold (STB_LOCAL)
ffffffff81946030-ffffffff81946062: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194bf70)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed
```
**Symbols:**

```
ffffffff8194be80-ffffffff8194bf69: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffffffff81c24d9b-ffffffff81c24dca: i2c_acpi_find_bus_speed.part.0.cold (STB_LOCAL)
ffffffff8194bf70-ffffffff8194bfa2: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8192fad0)
Location: drivers/i2c/i2c-core-acpi.c:331
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed
```
**Symbols:**

```
ffffffff8192f9e0-ffffffff8192fac9: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffffffff81c16e44-ffffffff81c16e73: i2c_acpi_find_bus_speed.part.0.cold (STB_LOCAL)
ffffffff8192fad0-ffffffff8192fb02: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d2da0)
Location: drivers/i2c/i2c-core-acpi.c:363
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed
```
**Symbols:**

```
ffffffff819d2cb0-ffffffff819d2d99: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffffffff81d25b3e-ffffffff81d25b6d: i2c_acpi_find_bus_speed.part.0.cold (STB_LOCAL)
ffffffff819d2da0-ffffffff819d2dd2: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:368
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed
```
**Symbols:**

```
ffffffff81ef189a-ffffffff81ef18c9: i2c_acpi_find_bus_speed.cold (STB_LOCAL)
ffffffff81b34ec0-ffffffff81b34ff5: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81cca000)
Location: drivers/i2c/i2c-core-acpi.c:388
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed
```
**Symbols:**

```
ffffffff81cca000-ffffffff81cca168: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d31d50)
Location: drivers/i2c/i2c-core-acpi.c:388
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed
```
**Symbols:**

```
ffffffff81d31d50-ffffffff81d31eb8: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de7d30)
Location: drivers/i2c/i2c-core-acpi.c:388
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed
```
**Symbols:**

```
ffffffff81de7d30-ffffffff81de7e98: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab57b8)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffff800010ab57b8-ffff800010ab58cc: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffff800010ab58d0-ffff800010ab591c: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/i2c.h:993
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/i2c.h:993
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/i2c.h:993
Inline: True
```
</details>
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
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818661c0)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff818660d0-ffffffff818661b9: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffffffff81866bf1-ffffffff81866c20: i2c_acpi_find_bus_speed.part.0.cold (STB_LOCAL)
ffffffff818661c0-ffffffff818661f0: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881470)
Location: drivers/i2c/i2c-core-acpi.c:335
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81881380-ffffffff81881469: i2c_acpi_find_bus_speed.part.0 (STB_LOCAL)
ffffffff81881ea1-ffffffff81881ed0: i2c_acpi_find_bus_speed.part.0.cold (STB_LOCAL)
ffffffff81881470-ffffffff818814a0: i2c_acpi_find_bus_speed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
