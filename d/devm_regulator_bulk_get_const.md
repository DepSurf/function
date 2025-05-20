# Function: <code>devm_regulator_bulk_get_const</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_regulator_bulk_get_const(struct device *dev, int num_consumers, const struct regulator_bulk_data *in_consumers, struct regulator_bulk_data **out_consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a44990)
Location: drivers/regulator/devres.c:272
Inline: False
```
**Symbols:**

```
ffffffff81a44990-ffffffff81a449ee: devm_regulator_bulk_get_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_regulator_bulk_get_const(struct device *dev, int num_consumers, const struct regulator_bulk_data *in_consumers, struct regulator_bulk_data **out_consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a8eb40)
Location: drivers/regulator/devres.c:272
Inline: False
```
**Symbols:**

```
ffffffff81a8eb40-ffffffff81a8eb9e: devm_regulator_bulk_get_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_regulator_bulk_get_const(struct device *dev, int num_consumers, const struct regulator_bulk_data *in_consumers, struct regulator_bulk_data **out_consumers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81ae13b0)
Location: drivers/regulator/devres.c:272
Inline: False
```
**Symbols:**

```
ffffffff81ae13b0-ffffffff81ae140e: devm_regulator_bulk_get_const (STB_GLOBAL)
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
