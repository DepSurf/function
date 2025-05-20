# Function: <code>_devm_regulator_get_enable</code>

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
int _devm_regulator_get_enable(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a44f90)
Location: drivers/regulator/devres.c:80
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_enable
  - drivers/regulator/devres.c:devm_regulator_get_enable_optional
```
**Symbols:**

```
ffffffff81a44f90-ffffffff81a45019: _devm_regulator_get_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _devm_regulator_get_enable(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a8f140)
Location: drivers/regulator/devres.c:80
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_enable
  - drivers/regulator/devres.c:devm_regulator_get_enable_optional
```
**Symbols:**

```
ffffffff81a8f140-ffffffff81a8f1d0: _devm_regulator_get_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _devm_regulator_get_enable(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81ae19b0)
Location: drivers/regulator/devres.c:80
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_enable
  - drivers/regulator/devres.c:devm_regulator_get_enable_optional
```
**Symbols:**

```
ffffffff81ae19b0-ffffffff81ae1a40: _devm_regulator_get_enable (STB_LOCAL)
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
