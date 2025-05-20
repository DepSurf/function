# Function: <code>regmap_get_spi_bus</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff819b0a60)
Location: drivers/base/regmap/regmap-spi.c:112
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
```
**Symbols:**

```
ffffffff819b0a60-ffffffff819b0b28: regmap_get_spi_bus.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_spi_bus(struct spi_device *spi, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81b247c0)
Location: drivers/base/regmap/regmap-spi.c:112
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
```
**Symbols:**

```
ffffffff81b247c0-ffffffff81b2490b: regmap_get_spi_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_spi_bus(struct spi_device *spi, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81b748d0)
Location: drivers/base/regmap/regmap-spi.c:112
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
```
**Symbols:**

```
ffffffff81b748d0-ffffffff81b74a18: regmap_get_spi_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct regmap_bus *regmap_get_spi_bus(struct spi_device *spi, const struct regmap_config *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (ffffffff81bc8720)
Location: drivers/base/regmap/regmap-spi.c:112
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-spi.c:__devm_regmap_init_spi
  - drivers/base/regmap/regmap-spi.c:__regmap_init_spi
```
**Symbols:**

```
ffffffff81bc8720-ffffffff81bc8868: regmap_get_spi_bus (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
