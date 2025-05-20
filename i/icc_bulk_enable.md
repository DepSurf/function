# Function: <code>icc_bulk_enable</code>

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
int icc_bulk_enable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff81c302f8-ffffffff81c3031a: icc_bulk_enable.cold (STB_LOCAL)
ffffffff819dcf00-ffffffff819dcf52: icc_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int icc_bulk_enable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff81c225d6-ffffffff81c225f8: icc_bulk_enable.cold (STB_LOCAL)
ffffffff819c3150-ffffffff819c31a2: icc_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int icc_bulk_enable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff81d3493e-ffffffff81d34960: icc_bulk_enable.cold (STB_LOCAL)
ffffffff81a729f0-ffffffff81a72a42: icc_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int icc_bulk_enable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff81f00d3b-ffffffff81f00d5d: icc_bulk_enable.cold (STB_LOCAL)
ffffffff81be4240-ffffffff81be429a: icc_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int icc_bulk_enable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81d90050)
Location: drivers/interconnect/bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff81d90050-ffffffff81d90113: icc_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int icc_bulk_enable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81dfe300)
Location: drivers/interconnect/bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff81dfe300-ffffffff81dfe3c3: icc_bulk_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int icc_bulk_enable(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81eb52f0)
Location: drivers/interconnect/bulk.c:86
Inline: False
```
**Symbols:**

```
ffffffff81eb52f0-ffffffff81eb53b3: icc_bulk_enable (STB_GLOBAL)
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
