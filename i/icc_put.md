# Function: <code>icc_put</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void icc_put(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:732
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/interconnect/core.c:devm_icc_release
```
**Symbols:**

```
ffffffff819dd607-ffffffff819dd621: icc_put.cold (STB_LOCAL)
ffffffff819dce90-ffffffff819dcf5e: icc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void icc_put(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:763
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/interconnect/core.c:devm_icc_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81c302c7-ffffffff81c302e1: icc_put.cold (STB_LOCAL)
ffffffff819dc5b0-ffffffff819dc67e: icc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void icc_put(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:763
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/interconnect/core.c:devm_icc_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81c225a5-ffffffff81c225bf: icc_put.cold (STB_LOCAL)
ffffffff819c2830-ffffffff819c28fe: icc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void icc_put(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:763
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/interconnect/core.c:devm_icc_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81d3490d-ffffffff81d34927: icc_put.cold (STB_LOCAL)
ffffffff81a720e0-ffffffff81a721ae: icc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void icc_put(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:763
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/interconnect/core.c:devm_icc_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81f00d0a-ffffffff81f00d24: icc_put.cold (STB_LOCAL)
ffffffff81be3bd0-ffffffff81be3cc1: icc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void icc_put(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8f900)
Location: drivers/interconnect/core.c:763
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/interconnect/core.c:devm_icc_release
  - drivers/interconnect/bulk.c:devm_icc_bulk_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81d8f900-ffffffff81d8fa0b: icc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void icc_put(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81dfdee0)
Location: drivers/interconnect/core.c:714
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/interconnect/core.c:devm_icc_release
  - drivers/interconnect/bulk.c:devm_icc_bulk_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81dfdee0-ffffffff81dfdfeb: icc_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void icc_put(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb4940)
Location: drivers/interconnect/core.c:781
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/interconnect/core.c:devm_icc_release
  - drivers/interconnect/bulk.c:devm_icc_bulk_release
  - drivers/interconnect/bulk.c:of_icc_bulk_get
```
**Symbols:**

```
ffffffff81eb4940-ffffffff81eb4a4b: icc_put (STB_GLOBAL)
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
