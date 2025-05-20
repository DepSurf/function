# Function: <code>of_parse_coupled_regulator</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:90
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:92
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:87
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:87
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:88
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:88
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:88
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:99
Inline: True
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
struct regulator_dev *of_parse_coupled_regulator(struct regulator_dev *rdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (ffff80001084bee8)
Location: drivers/regulator/of_regulator.c:617
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_coupling
```
**Symbols:**

```
ffff80001084bee8-ffff80001084bf78: of_parse_coupled_regulator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator_dev *of_parse_coupled_regulator(struct regulator_dev *rdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c09553f0)
Location: drivers/regulator/of_regulator.c:617
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_coupling
```
**Symbols:**

```
c09553f0-c0955458: of_parse_coupled_regulator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator_dev *of_parse_coupled_regulator(struct regulator_dev *rdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c0000000008ea3f0)
Location: drivers/regulator/of_regulator.c:617
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_coupling
```
**Symbols:**

```
c0000000008ea3f0-c0000000008ea4b0: of_parse_coupled_regulator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator_dev *of_parse_coupled_regulator(struct regulator_dev *rdev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (ffffffe00052b7f8)
Location: drivers/regulator/of_regulator.c:617
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_resolve_coupling
```
**Symbols:**

```
ffffffe00052b7f8-ffffffe00052b878: of_parse_coupled_regulator (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:87
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:87
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:87
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:87
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
