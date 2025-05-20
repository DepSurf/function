# Function: <code>device_node_get_regmap</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8174f605)
Location: drivers/mfd/syscon.c:152
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff8180dd30)
Location: drivers/mfd/syscon.c:151
Inline: True
Direct callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
```
**Symbols:**

```
ffffffff8180dd30-ffffffff8180ddd1: device_node_get_regmap.constprop.0 (STB_LOCAL)
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
In drivers/mfd/syscon.c (ffffffff8181ca60)
Location: drivers/mfd/syscon.c:153
Inline: True
Direct callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
```
**Symbols:**

```
ffffffff8181ca60-ffffffff8181cb01: device_node_get_regmap.constprop.0 (STB_LOCAL)
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
In drivers/mfd/syscon.c (ffffffff817ffe35)
Location: drivers/mfd/syscon.c:153
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff8188a225)
Location: drivers/mfd/syscon.c:153
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff819d3515)
Location: drivers/mfd/syscon.c:153
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff81b4d9b5)
Location: drivers/mfd/syscon.c:152
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff81ba0e25)
Location: drivers/mfd/syscon.c:167
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff81bf4f85)
Location: drivers/mfd/syscon.c:171
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct regmap *device_node_get_regmap(struct device_node *np, bool check_clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffff80001094ead8)
Location: drivers/mfd/syscon.c:152
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
```
**Symbols:**

```
ffff80001094ead8-ffff80001094ebe0: device_node_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regmap *device_node_get_regmap(struct device_node *np, bool check_clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (c0a388d0)
Location: drivers/mfd/syscon.c:152
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
```
**Symbols:**

```
c0a388d0-c0a3897c: device_node_get_regmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/syscon.c (c0000000009fb3b0)
Location: drivers/mfd/syscon.c:152
Inline: True
Direct callers:
  - drivers/mfd/syscon.c:syscon_node_to_regmap
  - drivers/mfd/syscon.c:device_node_to_regmap
```
**Symbols:**

```
c0000000009fb3b0-c0000000009fb4ec: device_node_get_regmap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regmap *device_node_get_regmap(struct device_node *np, bool check_clk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffe0005bf7f2)
Location: drivers/mfd/syscon.c:152
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
```
**Symbols:**

```
ffffffe0005bf7f2-ffffffe0005bf8b2: device_node_get_regmap (STB_LOCAL)
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
In drivers/mfd/syscon.c (ffffffff81704575)
Location: drivers/mfd/syscon.c:152
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff816d7ff5)
Location: drivers/mfd/syscon.c:152
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff81742ac5)
Location: drivers/mfd/syscon.c:152
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
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
In drivers/mfd/syscon.c (ffffffff8175df05)
Location: drivers/mfd/syscon.c:152
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
