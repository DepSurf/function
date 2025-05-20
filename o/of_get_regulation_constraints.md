# Function: <code>of_get_regulation_constraints</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/of_regulator.c (ffff80001084af38)
Location: drivers/regulator/of_regulator.c:24
Inline: True
Direct callers:
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
```
**Symbols:**

```
ffff80001084af38-ffff80001084b7c4: of_get_regulation_constraints.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_get_regulation_constraints(struct device *dev, struct device_node *np, struct regulator_init_data **init_data, const struct regulator_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c0954470)
Location: drivers/regulator/of_regulator.c:24
Inline: False
Direct callers:
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
```
**Symbols:**

```
c0954470-c0954d78: of_get_regulation_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/of_regulator.c (c0000000008e8ac0)
Location: drivers/regulator/of_regulator.c:24
Inline: True
Direct callers:
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
```
**Symbols:**

```
c0000000008e8ac0-c0000000008e95f8: of_get_regulation_constraints.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/of_regulator.c (ffffffe00052aab8)
Location: drivers/regulator/of_regulator.c:24
Inline: True
Direct callers:
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
```
**Symbols:**

```
ffffffe00052aab8-ffffffe00052b244: of_get_regulation_constraints.isra.0 (STB_LOCAL)
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
