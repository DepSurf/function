# Function: <code>devm_regmap_field_bulk_alloc</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_regmap_field_bulk_alloc(struct device *dev, struct regmap *regmap, struct regmap_field **rm_field, struct reg_field *reg_field, int num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817ef410)
Location: drivers/base/regmap/regmap.c:1321
Inline: False
```
**Symbols:**

```
ffffffff817ef410-ffffffff817ef4e2: devm_regmap_field_bulk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_regmap_field_bulk_alloc(struct device *dev, struct regmap *regmap, struct regmap_field **rm_field, struct reg_field *reg_field, int num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d3cb0)
Location: drivers/base/regmap/regmap.c:1321
Inline: False
```
**Symbols:**

```
ffffffff817d3cb0-ffffffff817d3d82: devm_regmap_field_bulk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devm_regmap_field_bulk_alloc(struct device *dev, struct regmap *regmap, struct regmap_field **rm_field, const struct reg_field *reg_field, int num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1360
Inline: False
```
**Symbols:**

```
ffffffff81d04601-ffffffff81d0463d: devm_regmap_field_bulk_alloc.cold (STB_LOCAL)
ffffffff8185f340-ffffffff8185f477: devm_regmap_field_bulk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devm_regmap_field_bulk_alloc(struct device *dev, struct regmap *regmap, struct regmap_field **rm_field, const struct reg_field *reg_field, int num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1379
Inline: False
```
**Symbols:**

```
ffffffff81eccfb1-ffffffff81eccff5: devm_regmap_field_bulk_alloc.cold (STB_LOCAL)
ffffffff819a7750-ffffffff819a78b8: devm_regmap_field_bulk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_regmap_field_bulk_alloc(struct device *dev, struct regmap *regmap, struct regmap_field **rm_field, const struct reg_field *reg_field, int num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b197c0)
Location: drivers/base/regmap/regmap.c:1381
Inline: False
```
**Symbols:**

```
ffffffff81b197c0-ffffffff81b198a2: devm_regmap_field_bulk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devm_regmap_field_bulk_alloc(struct device *dev, struct regmap *regmap, struct regmap_field **rm_field, const struct reg_field *reg_field, int num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1381
Inline: False
```
**Symbols:**

```
ffffffff82119e3b-ffffffff82119eaa: devm_regmap_field_bulk_alloc.cold (STB_LOCAL)
ffffffff81b69a80-ffffffff81b69c2f: devm_regmap_field_bulk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devm_regmap_field_bulk_alloc(struct device *dev, struct regmap *regmap, struct regmap_field **rm_field, const struct reg_field *reg_field, int num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1287
Inline: False
```
**Symbols:**

```
ffffffff821f7ce0-ffffffff821f7d4f: devm_regmap_field_bulk_alloc.cold (STB_LOCAL)
ffffffff81bbd740-ffffffff81bbd8ef: devm_regmap_field_bulk_alloc (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct reg_field *reg_field</code> ➡️ <code>const struct reg_field *reg_field</code>
</li>
</ul>
</details>
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
