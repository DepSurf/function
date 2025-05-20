# Function: <code>regulator_set_ramp_delay_regmap</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regulator_set_ramp_delay_regmap(struct regulator_dev *rdev, int ramp_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/helpers.c (ffffffff817311d0)
Location: drivers/regulator/helpers.c:946
Inline: False
```
**Symbols:**

```
ffffffff817311d0-ffffffff817312e6: regulator_set_ramp_delay_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_set_ramp_delay_regmap(struct regulator_dev *rdev, int ramp_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:946
Inline: False
```
**Symbols:**

```
ffffffff81cf832c-ffffffff81cf835a: regulator_set_ramp_delay_regmap.cold (STB_LOCAL)
ffffffff817b11e0-ffffffff817b12ff: regulator_set_ramp_delay_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_set_ramp_delay_regmap(struct regulator_dev *rdev, int ramp_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:946
Inline: False
```
**Symbols:**

```
ffffffff81ec0423-ffffffff81ec044d: regulator_set_ramp_delay_regmap.cold (STB_LOCAL)
ffffffff818ec920-ffffffff818eca8e: regulator_set_ramp_delay_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regulator_set_ramp_delay_regmap(struct regulator_dev *rdev, int ramp_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:946
Inline: False
```
**Symbols:**

```
ffffffff82094c3b-ffffffff82094c65: regulator_set_ramp_delay_regmap.cold (STB_LOCAL)
ffffffff81a43cf0-ffffffff81a43e55: regulator_set_ramp_delay_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regulator_set_ramp_delay_regmap(struct regulator_dev *rdev, int ramp_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:961
Inline: False
```
**Symbols:**

```
ffffffff82115a5f-ffffffff82115a8a: regulator_set_ramp_delay_regmap.cold (STB_LOCAL)
ffffffff81a8dee0-ffffffff81a8dff6: regulator_set_ramp_delay_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regulator_set_ramp_delay_regmap(struct regulator_dev *rdev, int ramp_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/helpers.c (0)
Location: drivers/regulator/helpers.c:964
Inline: False
```
**Symbols:**

```
ffffffff821f3789-ffffffff821f37b4: regulator_set_ramp_delay_regmap.cold (STB_LOCAL)
ffffffff81ae0880-ffffffff81ae0996: regulator_set_ramp_delay_regmap (STB_GLOBAL)
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
