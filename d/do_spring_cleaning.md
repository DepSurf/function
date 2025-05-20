# Function: <code>do_spring_cleaning</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_spring_cleaning(struct ce_array *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff817a4b10)
Location: drivers/ras/cec.c:140
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_timer_fn
```
**Symbols:**

```
ffffffff817a4b10-ffffffff817a4b70: do_spring_cleaning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff8181bf70)
Location: drivers/ras/cec.c:141
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_timer_fn
```
**Symbols:**

```
ffffffff8181bf70-ffffffff8181bfe3: do_spring_cleaning.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff81866060)
Location: drivers/ras/cec.c:141
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_timer_fn
```
**Symbols:**

```
ffffffff81866060-ffffffff818660d3: do_spring_cleaning.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff81885c30)
Location: drivers/ras/cec.c:141
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_timer_fn
```
**Symbols:**

```
ffffffff81885c30-ffffffff81885ca3: do_spring_cleaning.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff818d0200)
Location: drivers/ras/cec.c:141
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff818d0200-ffffffff818d0274: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff819025f0)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff819025f0-ffffffff81902664: do_spring_cleaning.constprop.0 (STB_LOCAL)
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
In drivers/ras/cec.c (ffffffff819d95b0)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff819d95b0-ffffffff819d9624: do_spring_cleaning.constprop.0 (STB_LOCAL)
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
In drivers/ras/cec.c (ffffffff819d8910)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff819d8910-ffffffff819d8984: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff819bea80)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff819bea80-ffffffff819beaf4: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff81a6e010)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff81a6e010-ffffffff81a6e084: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff81bdee30)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff81bdee30-ffffffff81bdeeb2: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff81d8a330)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff81d8a330-ffffffff81d8a3b2: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff81df8930)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff81df8930-ffffffff81df89b2: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff81eaf040)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff81eaf040-ffffffff81eaf0c2: do_spring_cleaning.constprop.0 (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff818a1a20)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff818a1a20-ffffffff818a1a94: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff8185d190)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff8185d190-ffffffff8185d204: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff818f3010)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff818f3010-ffffffff818f3084: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (ffffffff819140b0)
Location: drivers/ras/cec.c:142
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_work_fn
```
**Symbols:**

```
ffffffff819140b0-ffffffff81914124: do_spring_cleaning.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
