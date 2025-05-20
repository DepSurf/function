# Function: <code>of_icc_bulk_get</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int of_icc_bulk_get(struct device *dev, int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:15
Inline: False
```
**Symbols:**

```
ffffffff81c3031a-ffffffff81c30334: of_icc_bulk_get.cold (STB_LOCAL)
ffffffff819dcf60-ffffffff819dd026: of_icc_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int of_icc_bulk_get(struct device *dev, int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:15
Inline: False
```
**Symbols:**

```
ffffffff81c225f8-ffffffff81c22612: of_icc_bulk_get.cold (STB_LOCAL)
ffffffff819c31b0-ffffffff819c3276: of_icc_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int of_icc_bulk_get(struct device *dev, int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:15
Inline: False
```
**Symbols:**

```
ffffffff81d34960-ffffffff81d3497a: of_icc_bulk_get.cold (STB_LOCAL)
ffffffff81a72a50-ffffffff81a72b16: of_icc_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int of_icc_bulk_get(struct device *dev, int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:15
Inline: False
```
**Symbols:**

```
ffffffff81f00d5d-ffffffff81f00d78: of_icc_bulk_get.cold (STB_LOCAL)
ffffffff81be42a0-ffffffff81be4375: of_icc_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int of_icc_bulk_get(struct device *dev, int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81d901c0)
Location: drivers/interconnect/bulk.c:15
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:devm_of_icc_bulk_get
```
**Symbols:**

```
ffffffff81d901c0-ffffffff81d902a8: of_icc_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int of_icc_bulk_get(struct device *dev, int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81dfe470)
Location: drivers/interconnect/bulk.c:15
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:devm_of_icc_bulk_get
```
**Symbols:**

```
ffffffff81dfe470-ffffffff81dfe558: of_icc_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int of_icc_bulk_get(struct device *dev, int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81eb5460)
Location: drivers/interconnect/bulk.c:15
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:devm_of_icc_bulk_get
```
**Symbols:**

```
ffffffff81eb5460-ffffffff81eb5548: of_icc_bulk_get (STB_GLOBAL)
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
