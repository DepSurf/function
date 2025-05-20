# Function: <code>devm_regulator_irq_helper</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devm_regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff817b1e80)
Location: drivers/regulator/devres.c:450
Inline: False
```
**Symbols:**

```
ffffffff817b1e80-ffffffff817b1f06: devm_regulator_irq_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devm_regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff818ed6e0)
Location: drivers/regulator/devres.c:450
Inline: False
```
**Symbols:**

```
ffffffff818ed6e0-ffffffff818ed776: devm_regulator_irq_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devm_regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a44ee0)
Location: drivers/regulator/devres.c:672
Inline: False
```
**Symbols:**

```
ffffffff81a44ee0-ffffffff81a44f76: devm_regulator_irq_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devm_regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a8f090)
Location: drivers/regulator/devres.c:672
Inline: False
```
**Symbols:**

```
ffffffff81a8f090-ffffffff81a8f12d: devm_regulator_irq_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devm_regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81ae1900)
Location: drivers/regulator/devres.c:672
Inline: False
```
**Symbols:**

```
ffffffff81ae1900-ffffffff81ae199d: devm_regulator_irq_helper (STB_GLOBAL)
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
