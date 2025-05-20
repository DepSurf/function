# Function: <code>_allocate_opp_table</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d5072)
Location: drivers/opp/core.c:794
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181de52)
Location: drivers/opp/core.c:801
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849b52)
Location: drivers/opp/core.c:828
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188c904)
Location: drivers/opp/core.c:902
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bea74)
Location: drivers/opp/core.c:950
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8198fe80)
Location: drivers/opp/core.c:1028
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffff8198fe80-ffffffff8198fff7: _allocate_opp_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81993e20)
Location: drivers/opp/core.c:1061
Inline: True
Direct callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff81993e20-ffffffff81993fb2: _allocate_opp_table.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81978272)
Location: drivers/opp/core.c:1195
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a211f1)
Location: drivers/opp/core.c:1205
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8a16d)
Location: drivers/opp/core.c:1350
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d297ae)
Location: drivers/opp/core.c:1302
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d929ca)
Location: drivers/opp/core.c:1315
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e4a2aa)
Location: drivers/opp/core.c:1428
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b19c04)
Location: drivers/opp/core.c:950
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_get_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf48ac)
Location: drivers/opp/core.c:950
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_get_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0b730)
Location: drivers/opp/core.c:950
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_get_opp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe0007024c4)
Location: drivers/opp/core.c:950
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_get_opp_table
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81863194)
Location: drivers/opp/core.c:950
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182be44)
Location: drivers/opp/core.c:950
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b3f24)
Location: drivers/opp/core.c:950
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d01d4)
Location: drivers/opp/core.c:950
Inline: True
```
</details>
</li>
</ul>

## Differences
