# Function: <code>of_get_child_regulator</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:390
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
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:372
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
In drivers/regulator/core.c (ffffffff81676df2)
Location: drivers/regulator/core.c:372
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81727823)
Location: drivers/regulator/core.c:375
Inline: True
Inline callers:
  - drivers/regulator/core.c:of_get_regulator
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817442a3)
Location: drivers/regulator/core.c:374
Inline: True
Inline callers:
  - drivers/regulator/core.c:of_get_regulator
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
In drivers/regulator/core.c (ffffffff81727ccf)
Location: drivers/regulator/core.c:374
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff817a6e1f)
Location: drivers/regulator/core.c:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff818e13b0)
Location: drivers/regulator/core.c:365
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff81a36540)
Location: drivers/regulator/core.c:365
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff81a7fff0)
Location: drivers/regulator/core.c:431
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff81ad2560)
Location: drivers/regulator/core.c:433
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
struct device_node *of_get_child_regulator(struct device_node *parent, const char *prop_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff80001083fbb8)
Location: drivers/regulator/core.c:372
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/core.c:of_get_child_regulator
```
**Symbols:**

```
ffff80001083fbb8-ffff80001083fc50: of_get_child_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_get_child_regulator(struct device_node *parent, const char *prop_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0949414)
Location: drivers/regulator/core.c:372
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/core.c:of_get_child_regulator
```
**Symbols:**

```
c0949414-c0949498: of_get_child_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_get_child_regulator(struct device_node *parent, const char *prop_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008d9220)
Location: drivers/regulator/core.c:372
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/core.c:of_get_child_regulator
```
**Symbols:**

```
c0000000008d9220-c0000000008d9308: of_get_child_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_get_child_regulator(struct device_node *parent, const char *prop_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000521bb6)
Location: drivers/regulator/core.c:372
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_dev_lookup
  - drivers/regulator/core.c:of_get_child_regulator
```
**Symbols:**

```
ffffffe000521bb6-ffffffe000521c28: of_get_child_regulator (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff8163cae2)
Location: drivers/regulator/core.c:372
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff8161ccd2)
Location: drivers/regulator/core.c:372
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff8166ac32)
Location: drivers/regulator/core.c:372
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff816851f2)
Location: drivers/regulator/core.c:372
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
