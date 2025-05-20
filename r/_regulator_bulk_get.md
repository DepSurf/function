# Function: <code>_regulator_bulk_get</code>

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
int _regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a42ad0)
Location: drivers/regulator/core.c:4789
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81a42ad0-ffffffff81a42ddb: _regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8cbc0)
Location: drivers/regulator/core.c:4855
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81a8cbc0-ffffffff81a8ceed: _regulator_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _regulator_bulk_get(struct device *dev, int num_consumers, struct regulator_bulk_data *consumers, enum regulator_get_type get_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adf3c0)
Location: drivers/regulator/core.c:4877
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/devres.c:_devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff81adf3c0-ffffffff81adf6ed: _regulator_bulk_get (STB_GLOBAL)
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
