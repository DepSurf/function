# Function: <code>_opp_compare_key</code>

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
int _opp_compare_key(struct dev_pm_opp *opp1, struct dev_pm_opp *opp2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198e03b)
Location: drivers/opp/core.c:1378
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_is_duplicate
  - drivers/opp/core.c:_opp_is_duplicate
```
**Symbols:**

```
ffffffff81990a70-ffffffff81990ab5: _opp_compare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int _opp_compare_key(struct dev_pm_opp *opp1, struct dev_pm_opp *opp2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81991bfb)
Location: drivers/opp/core.c:1462
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_is_duplicate
  - drivers/opp/core.c:_opp_is_duplicate
```
**Symbols:**

```
ffffffff81994810-ffffffff81994855: _opp_compare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int _opp_compare_key(struct dev_pm_opp *opp1, struct dev_pm_opp *opp2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81978e40)
Location: drivers/opp/core.c:1619
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81978e40-ffffffff81978e85: _opp_compare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int _opp_compare_key(struct dev_pm_opp *opp1, struct dev_pm_opp *opp2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a21dc0)
Location: drivers/opp/core.c:1629
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81a21dc0-ffffffff81a21e05: _opp_compare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int _opp_compare_key(struct dev_pm_opp *opp1, struct dev_pm_opp *opp2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8ae70)
Location: drivers/opp/core.c:1773
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81b8ae70-ffffffff81b8aec1: _opp_compare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int _opp_compare_key(struct opp_table *opp_table, struct dev_pm_opp *opp1, struct dev_pm_opp *opp2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d2a430)
Location: drivers/opp/core.c:1788
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81d2a430-ffffffff81d2a4cd: _opp_compare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int _opp_compare_key(struct opp_table *opp_table, struct dev_pm_opp *opp1, struct dev_pm_opp *opp2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d93620)
Location: drivers/opp/core.c:1796
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81d93620-ffffffff81d936bd: _opp_compare_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int _opp_compare_key(struct opp_table *opp_table, struct dev_pm_opp *opp1, struct dev_pm_opp *opp2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e4b070)
Location: drivers/opp/core.c:1908
Inline: True
Direct callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81e4b070-ffffffff81e4b10d: _opp_compare_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct opp_table *opp_table</code>
</li>
<li>
<b>Param reordered. </b>
<code>opp1, opp2</code> ➡️ <code>opp_table, opp1, opp2</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
