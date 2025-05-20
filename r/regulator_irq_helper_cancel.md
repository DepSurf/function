# Function: <code>regulator_irq_helper_cancel</code>

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
void regulator_irq_helper_cancel(void **handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff817b1f10)
Location: drivers/regulator/irq_helpers.c:385
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff817b1f10-ffffffff817b1f4f: regulator_irq_helper_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void regulator_irq_helper_cancel(void **handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff818ed860)
Location: drivers/regulator/irq_helpers.c:387
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff818ed860-ffffffff818ed8bd: regulator_irq_helper_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void regulator_irq_helper_cancel(void **handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff81a45360)
Location: drivers/regulator/irq_helpers.c:387
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff81a45360-ffffffff81a453bd: regulator_irq_helper_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void regulator_irq_helper_cancel(void **handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff81a8f510)
Location: drivers/regulator/irq_helpers.c:387
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff81a8f510-ffffffff81a8f56d: regulator_irq_helper_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void regulator_irq_helper_cancel(void **handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/irq_helpers.c (ffffffff81ae1d80)
Location: drivers/regulator/irq_helpers.c:387
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_irq_helper
```
**Symbols:**

```
ffffffff81ae1d80-ffffffff81ae1ddd: regulator_irq_helper_cancel (STB_GLOBAL)
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
