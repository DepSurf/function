# Function: <code>regulator_irq_helper</code>

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
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff817b2140)
Location: drivers/regulator/irq_helpers.c:336
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff817b1f50-ffffffff817b2138: regulator_irq_helper.part.0 (STB_LOCAL)
ffffffff81cf843c-ffffffff81cf845a: regulator_irq_helper.part.0.cold (STB_LOCAL)
ffffffff817b2140-ffffffff817b2179: regulator_irq_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff818edaa0)
Location: drivers/regulator/irq_helpers.c:338
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff818ed8c0-ffffffff818eda9e: regulator_irq_helper.part.0 (STB_LOCAL)
ffffffff81ec053f-ffffffff81ec055e: regulator_irq_helper.part.0.cold (STB_LOCAL)
ffffffff818edaa0-ffffffff818edaee: regulator_irq_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff81a453d0)
Location: drivers/regulator/irq_helpers.c:338
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff81a453d0-ffffffff81a455cb: regulator_irq_helper.part.0 (STB_LOCAL)
ffffffff81a455e0-ffffffff81a4562e: regulator_irq_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff81a8f580)
Location: drivers/regulator/irq_helpers.c:338
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff81a8f580-ffffffff81a8f77c: regulator_irq_helper.part.0 (STB_LOCAL)
ffffffff81a8f790-ffffffff81a8f7de: regulator_irq_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *regulator_irq_helper(struct device *dev, const struct regulator_irq_desc *d, int irq, int irq_flags, int common_errs, int *per_rdev_errs, struct regulator_dev **rdev, int rdev_amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff81ae1df0)
Location: drivers/regulator/irq_helpers.c:338
Inline: True
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff81ae1df0-ffffffff81ae1fec: regulator_irq_helper.part.0 (STB_LOCAL)
ffffffff81ae2000-ffffffff81ae204e: regulator_irq_helper (STB_GLOBAL)
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
