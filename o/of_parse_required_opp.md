# Function: <code>of_parse_required_opp</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_parse_required_opp(struct device_node *np, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffff800010b1b318)
Location: drivers/opp/of.c:95
Inline: True
Direct callers:
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:_of_init_opp_table
```
**Symbols:**

```
ffff800010b1b318-ffff800010b1b388: of_parse_required_opp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_parse_required_opp(struct device_node *np, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c0bf5ea8)
Location: drivers/opp/of.c:95
Inline: True
Direct callers:
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:_of_init_opp_table
```
**Symbols:**

```
c0bf5ea8-c0bf5f04: of_parse_required_opp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_parse_required_opp(struct device_node *np, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (c000000000c0d890)
Location: drivers/opp/of.c:95
Inline: True
Direct callers:
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:_of_init_opp_table
```
**Symbols:**

```
c000000000c0d890-c000000000c0d920: of_parse_required_opp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_parse_required_opp(struct device_node *np, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/of.c (ffffffe0007038be)
Location: drivers/opp/of.c:95
Inline: True
Direct callers:
  - drivers/opp/of.c:of_get_required_opp_performance_state
  - drivers/opp/of.c:_of_init_opp_table
```
**Symbols:**

```
ffffffe0007038be-ffffffe000703920: of_parse_required_opp (STB_LOCAL)
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
