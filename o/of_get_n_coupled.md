# Function: <code>of_get_n_coupled</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int of_get_n_coupled(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (ffff80001084bd20)
Location: drivers/regulator/of_regulator.c:486
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_check_coupling_data
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffff80001084bca8-ffff80001084bce8: of_get_n_coupled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int of_get_n_coupled(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c0955248)
Location: drivers/regulator/of_regulator.c:486
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_check_coupling_data
Direct callers:
  - drivers/regulator/core.c:regulator_init_coupling
```
**Symbols:**

```
c09551d4-c0955204: of_get_n_coupled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int of_get_n_coupled(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c0000000008ea164)
Location: drivers/regulator/of_regulator.c:486
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_check_coupling_data
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
c0000000008ea0c0-c0000000008ea114: of_get_n_coupled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int of_get_n_coupled(struct regulator_dev *rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (ffffffe00052b684)
Location: drivers/regulator/of_regulator.c:486
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_check_coupling_data
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffe00052b618-ffffffe00052b658: of_get_n_coupled (STB_GLOBAL)
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
