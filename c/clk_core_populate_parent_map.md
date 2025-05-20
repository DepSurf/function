# Function: <code>clk_core_populate_parent_map</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162e240)
Location: drivers/clk/clk.c:3510
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff8162e240-ffffffff8162e41f: clk_core_populate_parent_map.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81651f3b)
Location: drivers/clk/clk.c:3559
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clk_core_populate_parent_map(struct clk_core *core, const struct clk_init_data *init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fd340)
Location: drivers/clk/clk.c:3649
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff816fd340-ffffffff816fd50c: clk_core_populate_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clk_core_populate_parent_map(struct clk_core *core, const struct clk_init_data *init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171a2f0)
Location: drivers/clk/clk.c:3718
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff8171a2f0-ffffffff8171a4bc: clk_core_populate_parent_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clk_core_populate_parent_map(struct clk_core *core, const struct clk_init_data *init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fb5f0)
Location: drivers/clk/clk.c:3727
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff816fb5f0-ffffffff816fb7c2: clk_core_populate_parent_map (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81775c80)
Location: drivers/clk/clk.c:3755
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff81775c80-ffffffff81775e52: clk_core_populate_parent_map.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff818ac450)
Location: drivers/clk/clk.c:3828
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff818ac450-ffffffff818ac621: clk_core_populate_parent_map.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff819f7bd0)
Location: drivers/clk/clk.c:4017
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff819f7bd0-ffffffff819f7da1: clk_core_populate_parent_map.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81a40490)
Location: drivers/clk/clk.c:4069
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff81a40490-ffffffff81a40658: clk_core_populate_parent_map.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81a8beb0)
Location: drivers/clk/clk.c:4115
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffff81a8beb0-ffffffff81a8c078: clk_core_populate_parent_map.constprop.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffff8000107c2ab4)
Location: drivers/clk/clk.c:3559
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
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
In drivers/clk/clk.c (c08ed724)
Location: drivers/clk/clk.c:3559
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe0005104fe)
Location: drivers/clk/clk.c:3559
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
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
In drivers/clk/clk.c (ffffffff81617f9b)
Location: drivers/clk/clk.c:3559
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
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
In drivers/clk/clk.c (ffffffff8160c4cb)
Location: drivers/clk/clk.c:3559
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
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
In drivers/clk/clk.c (ffffffff81645d7b)
Location: drivers/clk/clk.c:3559
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
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
In drivers/clk/clk.c (ffffffff8166030b)
Location: drivers/clk/clk.c:3559
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
```
</details>
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
</ul>
