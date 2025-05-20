# Function: <code>clk_core_get_scaled_duty_cycle</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f9990)
Location: drivers/clk/clk.c:2649
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff815f9990-ffffffff815f99ee: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162bd40)
Location: drivers/clk/clk.c:2789
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff8162bd40-ffffffff8162bd9e: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164f010)
Location: drivers/clk/clk.c:2803
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff8164f010-ffffffff8164f06e: clk_core_get_scaled_duty_cycle (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816feb31)
Location: drivers/clk/clk.c:2832
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_one
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
In drivers/clk/clk.c (ffffffff8171bb54)
Location: drivers/clk/clk.c:2847
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_one
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
In drivers/clk/clk.c (ffffffff816fd207)
Location: drivers/clk/clk.c:2860
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
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
In drivers/clk/clk.c (ffffffff81778537)
Location: drivers/clk/clk.c:2860
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
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
In drivers/clk/clk.c (ffffffff818aeadf)
Location: drivers/clk/clk.c:2877
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
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
In drivers/clk/clk.c (ffffffff819fa2bf)
Location: drivers/clk/clk.c:3067
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
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
In drivers/clk/clk.c (ffffffff81a4296f)
Location: drivers/clk/clk.c:3112
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
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
In drivers/clk/clk.c (ffffffff81a8e1a6)
Location: drivers/clk/clk.c:3112
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_one
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
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bd540)
Location: drivers/clk/clk.c:2803
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffff8000107bd540-ffff8000107bd5a4: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e9f78)
Location: drivers/clk/clk.c:2803
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
c08e9f78-c08e9fe0: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050cae4)
Location: drivers/clk/clk.c:2803
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffe00050cae4-ffffffe00050cb4c: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81615070)
Location: drivers/clk/clk.c:2803
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff81615070-ffffffff816150ce: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816095a0)
Location: drivers/clk/clk.c:2803
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff816095a0-ffffffff816095fe: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81642e50)
Location: drivers/clk/clk.c:2803
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff81642e50-ffffffff81642eae: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clk_core_get_scaled_duty_cycle(struct clk_core *core, unsigned int scale);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165d290)
Location: drivers/clk/clk.c:2803
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff8165d290-ffffffff8165d2ee: clk_core_get_scaled_duty_cycle (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
