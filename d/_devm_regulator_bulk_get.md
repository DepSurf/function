# Function: <code>_devm_regulator_bulk_get</code>

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
int _devm_regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers, enum regulator_get_type get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a44810)
Location: drivers/regulator/devres.c:189
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_const
  - drivers/regulator/devres.c:devm_regulator_bulk_get_exclusive
```
**Symbols:**

```
ffffffff81a44810-ffffffff81a448cc: _devm_regulator_bulk_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _devm_regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers, enum regulator_get_type get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a8e9c0)
Location: drivers/regulator/devres.c:189
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_const
  - drivers/regulator/devres.c:devm_regulator_bulk_get_exclusive
```
**Symbols:**

```
ffffffff81a8e9c0-ffffffff81a8ea7c: _devm_regulator_bulk_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _devm_regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers, enum regulator_get_type get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81ae1230)
Location: drivers/regulator/devres.c:189
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_const
  - drivers/regulator/devres.c:devm_regulator_bulk_get_exclusive
```
**Symbols:**

```
ffffffff81ae1230-ffffffff81ae12ec: _devm_regulator_bulk_get (STB_LOCAL)
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
