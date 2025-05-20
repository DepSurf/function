# Function: <code>of_get_regulator_init_data</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct regulator_init_data *of_get_regulator_init_data(struct device *dev, struct device_node *node, const struct regulator_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (ffff80001084b7c8)
Location: drivers/regulator/of_regulator.c:273
Inline: False
Direct callers:
  - drivers/regulator/of_regulator.c:regulator_of_get_init_data
```
**Symbols:**

```
ffff80001084b7c8-ffff80001084b84c: of_get_regulator_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator_init_data *of_get_regulator_init_data(struct device *dev, struct device_node *node, const struct regulator_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c0954d78)
Location: drivers/regulator/of_regulator.c:273
Inline: False
Direct callers:
  - drivers/regulator/of_regulator.c:regulator_of_get_init_data
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/twl-regulator.c:twlreg_probe
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
```
**Symbols:**

```
c0954d78-c0954e18: of_get_regulator_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator_init_data *of_get_regulator_init_data(struct device *dev, struct device_node *node, const struct regulator_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c0000000008e9600)
Location: drivers/regulator/of_regulator.c:273
Inline: False
Direct callers:
  - drivers/regulator/of_regulator.c:regulator_of_get_init_data
```
**Symbols:**

```
c0000000008e9600-c0000000008e96bc: of_get_regulator_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator_init_data *of_get_regulator_init_data(struct device *dev, struct device_node *node, const struct regulator_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (ffffffe00052b244)
Location: drivers/regulator/of_regulator.c:273
Inline: False
Direct callers:
  - drivers/regulator/of_regulator.c:regulator_of_get_init_data
```
**Symbols:**

```
ffffffe00052b244-ffffffe00052b2a8: of_get_regulator_init_data (STB_GLOBAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
