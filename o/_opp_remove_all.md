# Function: <code>_opp_remove_all</code>

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
void _opp_remove_all(struct opp_table *opp_table, bool dynamic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81991fb0)
Location: drivers/opp/core.c:1357
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff81991fb0-ffffffff819920cd: _opp_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _opp_remove_all(struct opp_table *opp_table, bool dynamic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819765e0)
Location: drivers/opp/core.c:1514
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff819765e0-ffffffff819766fd: _opp_remove_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void _opp_remove_all(struct opp_table *opp_table, bool dynamic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1524
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff81a1f380-ffffffff81a1f4a8: _opp_remove_all (STB_LOCAL)
ffffffff81d2b1d2-ffffffff81d2b208: _opp_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void _opp_remove_all(struct opp_table *opp_table, bool dynamic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1668
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff81b87e60-ffffffff81b87f9c: _opp_remove_all (STB_LOCAL)
ffffffff81ef73bb-ffffffff81ef73f1: _opp_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void _opp_remove_all(struct opp_table *opp_table, bool dynamic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1644
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff81d27540-ffffffff81d2767c: _opp_remove_all (STB_LOCAL)
ffffffff820a8a33-ffffffff820a8a69: _opp_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void _opp_remove_all(struct opp_table *opp_table, bool dynamic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1652
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff81d906e0-ffffffff81d9081c: _opp_remove_all (STB_LOCAL)
ffffffff82129c09-ffffffff82129c3f: _opp_remove_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void _opp_remove_all(struct opp_table *opp_table, bool dynamic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1762
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
**Symbols:**

```
ffffffff81e47d40-ffffffff81e47e7c: _opp_remove_all (STB_LOCAL)
ffffffff8220b952-ffffffff8220b988: _opp_remove_all.cold (STB_LOCAL)
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
