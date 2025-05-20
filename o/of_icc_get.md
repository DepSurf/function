# Function: <code>of_icc_get</code>

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
struct icc_path *of_icc_get(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dbb91)
Location: drivers/interconnect/core.c:502
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
```
**Symbols:**

```
ffffffff819db9b0-ffffffff819db9d8: of_icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct icc_path *of_icc_get(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819db291)
Location: drivers/interconnect/core.c:533
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
Direct callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff819dafb0-ffffffff819dafd8: of_icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct icc_path *of_icc_get(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c1541)
Location: drivers/interconnect/core.c:533
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
Direct callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff819c1250-ffffffff819c1278: of_icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct icc_path *of_icc_get(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81a70d18)
Location: drivers/interconnect/core.c:533
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
Direct callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81a70a10-ffffffff81a70a38: of_icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct icc_path *of_icc_get(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be23b7)
Location: drivers/interconnect/core.c:533
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
Direct callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81be1f80-ffffffff81be1fb4: of_icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct icc_path *of_icc_get(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8de57)
Location: drivers/interconnect/core.c:533
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
Direct callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81d8d9e0-ffffffff81d8da14: of_icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct icc_path *of_icc_get(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81dfc717)
Location: drivers/interconnect/core.c:532
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
Direct callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81dfc1b0-ffffffff81dfc1e4: of_icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct icc_path *of_icc_get(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb3167)
Location: drivers/interconnect/core.c:551
Inline: True
Inline callers:
  - drivers/interconnect/core.c:devm_of_icc_get
Direct callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81eb2bf0-ffffffff81eb2c24: of_icc_get (STB_GLOBAL)
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
