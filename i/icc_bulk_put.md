# Function: <code>icc_bulk_put</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_put(int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff819dcfc4)
Location: drivers/interconnect/bulk.c:46
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff819dce00-ffffffff819dce51: icc_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_put(int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff819c3214)
Location: drivers/interconnect/bulk.c:46
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff819c3050-ffffffff819c30a1: icc_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_put(int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81a72ab4)
Location: drivers/interconnect/bulk.c:46
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81a728f0-ffffffff81a72941: icc_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_put(int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81be430b)
Location: drivers/interconnect/bulk.c:46
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81be4110-ffffffff81be4175: icc_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_put(int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81d9013b)
Location: drivers/interconnect/bulk.c:46
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:devm_icc_bulk_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81d8fed0-ffffffff81d8ff35: icc_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_put(int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81dfe3eb)
Location: drivers/interconnect/bulk.c:46
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:devm_icc_bulk_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81dfe180-ffffffff81dfe1e5: icc_bulk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_put(int num_paths, struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81eb53db)
Location: drivers/interconnect/bulk.c:46
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:devm_icc_bulk_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81eb5170-ffffffff81eb51d5: icc_bulk_put (STB_GLOBAL)
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
