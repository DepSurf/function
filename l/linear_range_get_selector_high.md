# Function: <code>linear_range_get_selector_high</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int linear_range_get_selector_high(const struct linear_range *r, unsigned int val, unsigned int *selector, bool *found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/linear_ranges.c (ffffffff8159a0c0)
Location: lib/linear_ranges.c:219
Inline: True
```
**Symbols:**

```
ffffffff8159a0c0-ffffffff8159a112: linear_range_get_selector_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int linear_range_get_selector_high(const struct linear_range *r, unsigned int val, unsigned int *selector, bool *found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/linear_ranges.c (ffffffff815b5ad0)
Location: lib/linear_ranges.c:219
Inline: True
```
**Symbols:**

```
ffffffff815b5ad0-ffffffff815b5b22: linear_range_get_selector_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int linear_range_get_selector_high(const struct linear_range *r, unsigned int val, unsigned int *selector, bool *found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/linear_ranges.c (ffffffff815c08b0)
Location: lib/linear_ranges.c:219
Inline: True
```
**Symbols:**

```
ffffffff815c08b0-ffffffff815c0902: linear_range_get_selector_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int linear_range_get_selector_high(const struct linear_range *r, unsigned int val, unsigned int *selector, bool *found);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/linear_ranges.c (ffffffff816285e0)
Location: lib/linear_ranges.c:219
Inline: True
```
**Symbols:**

```
ffffffff816285e0-ffffffff81628632: linear_range_get_selector_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int linear_range_get_selector_high(const struct linear_range *r, unsigned int val, unsigned int *selector, bool *found);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/linear_ranges.c (ffffffff816f92b0)
Location: lib/linear_ranges.c:219
Inline: False
Direct callers:
  - drivers/regulator/helpers.c:regulator_map_voltage_linear_range
```
**Symbols:**

```
ffffffff816f92b0-ffffffff816f9333: linear_range_get_selector_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int linear_range_get_selector_high(const struct linear_range *r, unsigned int val, unsigned int *selector, bool *found);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/linear_ranges.c (ffffffff817ebbc0)
Location: lib/linear_ranges.c:219
Inline: False
Direct callers:
  - drivers/regulator/helpers.c:regulator_map_voltage_linear_range
```
**Symbols:**

```
ffffffff817ebbc0-ffffffff817ebc43: linear_range_get_selector_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int linear_range_get_selector_high(const struct linear_range *r, unsigned int val, unsigned int *selector, bool *found);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/linear_ranges.c (ffffffff8182bd40)
Location: lib/linear_ranges.c:219
Inline: False
Direct callers:
  - drivers/regulator/helpers.c:regulator_map_voltage_linear_range
```
**Symbols:**

```
ffffffff8182bd40-ffffffff8182bdc7: linear_range_get_selector_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int linear_range_get_selector_high(const struct linear_range *r, unsigned int val, unsigned int *selector, bool *found);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/linear_ranges.c (ffffffff8187d920)
Location: lib/linear_ranges.c:219
Inline: False
Direct callers:
  - drivers/regulator/helpers.c:regulator_map_voltage_linear_range
```
**Symbols:**

```
ffffffff8187d920-ffffffff8187d9a7: linear_range_get_selector_high (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
