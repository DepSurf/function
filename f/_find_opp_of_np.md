# Function: <code>_find_opp_of_np</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dev_pm_opp *_find_opp_of_np(struct opp_table *opp_table, struct device_node *opp_np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffff800010b1b1a0)
Location: drivers/opp/of.c:75
Inline: False
Direct callers:
  - drivers/opp/of.c:of_get_required_opp_performance_state
```
**Symbols:**

```
ffff800010b1b1a0-ffff800010b1b23c: _find_opp_of_np (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dev_pm_opp *_find_opp_of_np(struct opp_table *opp_table, struct device_node *opp_np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c0bf5bac)
Location: drivers/opp/of.c:75
Inline: False
Direct callers:
  - drivers/opp/of.c:of_get_required_opp_performance_state
```
**Symbols:**

```
c0bf5bac-c0bf5c2c: _find_opp_of_np (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dev_pm_opp *_find_opp_of_np(struct opp_table *opp_table, struct device_node *opp_np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0d3c0)
Location: drivers/opp/of.c:75
Inline: False
Direct callers:
  - drivers/opp/of.c:of_get_required_opp_performance_state
```
**Symbols:**

```
c000000000c0d3c0-c000000000c0d4a0: _find_opp_of_np (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dev_pm_opp *_find_opp_of_np(struct opp_table *opp_table, struct device_node *opp_np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffffffe0007035d0)
Location: drivers/opp/of.c:75
Inline: False
Direct callers:
  - drivers/opp/of.c:of_get_required_opp_performance_state
```
**Symbols:**

```
ffffffe0007035d0-ffffffe00070364a: _find_opp_of_np (STB_LOCAL)
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
