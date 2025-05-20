# Function: <code>_opp_table_free_required_tables</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/of.c (ffff800010b1b490)
Location: drivers/opp/of.c:136
Inline: True
Direct callers:
  - drivers/opp/of.c:_of_clear_opp_table
  - drivers/opp/of.c:_of_init_opp_table
```
**Symbols:**

```
ffff800010b1b490-ffff800010b1b50c: _opp_table_free_required_tables.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _opp_table_free_required_tables(struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c0bf5b10)
Location: drivers/opp/of.c:136
Inline: False
Direct callers:
  - drivers/opp/of.c:_of_clear_opp_table
  - drivers/opp/of.c:_of_init_opp_table
```
**Symbols:**

```
c0bf5b10-c0bf5b90: _opp_table_free_required_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _opp_table_free_required_tables(struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0d2b0)
Location: drivers/opp/of.c:136
Inline: False
Direct callers:
  - drivers/opp/of.c:_of_clear_opp_table
  - drivers/opp/of.c:_of_init_opp_table
```
**Symbols:**

```
c000000000c0d2b0-c000000000c0d380: _opp_table_free_required_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _opp_table_free_required_tables(struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffffffe000703532)
Location: drivers/opp/of.c:136
Inline: False
Direct callers:
  - drivers/opp/of.c:_of_clear_opp_table
  - drivers/opp/of.c:_of_init_opp_table
```
**Symbols:**

```
ffffffe000703532-ffffffe0007035a6: _opp_table_free_required_tables (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
