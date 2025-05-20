# Function: <code>icc_bulk_disable</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void icc_bulk_disable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff819dceb0)
Location: drivers/interconnect/bulk.c:112
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff819dceb0-ffffffff819dcef9: icc_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void icc_bulk_disable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff819c3100)
Location: drivers/interconnect/bulk.c:112
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff819c3100-ffffffff819c3149: icc_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void icc_bulk_disable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81a729a0)
Location: drivers/interconnect/bulk.c:112
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81a729a0-ffffffff81a729e9: icc_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void icc_bulk_disable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81be41e0)
Location: drivers/interconnect/bulk.c:112
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81be41e0-ffffffff81be423d: icc_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_disable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81d900a6)
Location: drivers/interconnect/bulk.c:112
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81d8ffe0-ffffffff81d9003d: icc_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_disable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81dfe356)
Location: drivers/interconnect/bulk.c:112
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81dfe290-ffffffff81dfe2ed: icc_bulk_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void icc_bulk_disable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81eb5346)
Location: drivers/interconnect/bulk.c:112
Inline: True
Inline callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81eb5280-ffffffff81eb52dd: icc_bulk_disable (STB_GLOBAL)
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
