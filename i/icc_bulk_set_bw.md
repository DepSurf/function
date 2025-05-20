# Function: <code>icc_bulk_set_bw</code>

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
int icc_bulk_set_bw(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:62
Inline: False
```
**Symbols:**

```
ffffffff81c302e1-ffffffff81c302f8: icc_bulk_set_bw.cold (STB_LOCAL)
ffffffff819dce60-ffffffff819dceb0: icc_bulk_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int icc_bulk_set_bw(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:62
Inline: False
```
**Symbols:**

```
ffffffff81c225bf-ffffffff81c225d6: icc_bulk_set_bw.cold (STB_LOCAL)
ffffffff819c30b0-ffffffff819c3100: icc_bulk_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int icc_bulk_set_bw(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:62
Inline: False
```
**Symbols:**

```
ffffffff81d34927-ffffffff81d3493e: icc_bulk_set_bw.cold (STB_LOCAL)
ffffffff81a72950-ffffffff81a729a0: icc_bulk_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int icc_bulk_set_bw(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/bulk.c (0)
Location: drivers/interconnect/bulk.c:62
Inline: False
```
**Symbols:**

```
ffffffff81f00d24-ffffffff81f00d3b: icc_bulk_set_bw.cold (STB_LOCAL)
ffffffff81be4180-ffffffff81be41d9: icc_bulk_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int icc_bulk_set_bw(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81d8ff50)
Location: drivers/interconnect/bulk.c:62
Inline: False
```
**Symbols:**

```
ffffffff81d8ff50-ffffffff81d8ffcd: icc_bulk_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int icc_bulk_set_bw(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81dfe200)
Location: drivers/interconnect/bulk.c:62
Inline: False
```
**Symbols:**

```
ffffffff81dfe200-ffffffff81dfe27d: icc_bulk_set_bw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int icc_bulk_set_bw(int num_paths, const struct icc_bulk_data *paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/bulk.c (ffffffff81eb51f0)
Location: drivers/interconnect/bulk.c:62
Inline: False
```
**Symbols:**

```
ffffffff81eb51f0-ffffffff81eb526d: icc_bulk_set_bw (STB_GLOBAL)
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
