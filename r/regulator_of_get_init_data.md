# Function: <code>regulator_of_get_init_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/internal.h:45
Inline: True
```
</details>
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
Location: drivers/regulator/internal.h:81
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
Location: drivers/regulator/internal.h:83
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
Location: drivers/regulator/internal.h:78
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
Location: drivers/regulator/internal.h:78
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
Location: drivers/regulator/internal.h:79
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
Location: drivers/regulator/internal.h:79
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
Location: drivers/regulator/internal.h:79
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
Location: drivers/regulator/internal.h:90
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
Location: drivers/regulator/internal.h:90
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
Location: drivers/regulator/internal.h:90
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
Location: drivers/regulator/internal.h:90
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
Location: drivers/regulator/internal.h:90
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
struct regulator_init_data *regulator_of_get_init_data(struct device *dev, const struct regulator_desc *desc, struct regulator_config *config, struct device_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (ffff80001084ba30)
Location: drivers/regulator/of_regulator.c:430
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffff80001084ba30-ffff80001084bc54: regulator_of_get_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator_init_data *regulator_of_get_init_data(struct device *dev, const struct regulator_desc *desc, struct regulator_config *config, struct device_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c0954fc4)
Location: drivers/regulator/of_regulator.c:430
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
c0954fc4-c0955198: regulator_of_get_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator_init_data *regulator_of_get_init_data(struct device *dev, const struct regulator_desc *desc, struct regulator_config *config, struct device_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (c0000000008e9af0)
Location: drivers/regulator/of_regulator.c:430
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
c0000000008e9af0-c0000000008ea058: regulator_of_get_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator_init_data *regulator_of_get_init_data(struct device *dev, const struct regulator_desc *desc, struct regulator_config *config, struct device_node **node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/of_regulator.c (ffffffe00052b43a)
Location: drivers/regulator/of_regulator.c:430
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffe00052b43a-ffffffe00052b5d6: regulator_of_get_init_data (STB_GLOBAL)
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
Location: drivers/regulator/internal.h:78
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
Location: drivers/regulator/internal.h:78
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
Location: drivers/regulator/internal.h:78
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
Location: drivers/regulator/internal.h:78
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
