# Function: <code>clk_core_set_duty_cycle_parent_nolock</code>

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
In drivers/clk/clk.c (ffffffff815f91cb)
Location: drivers/clk/clk.c:2593
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8162b33b)
Location: drivers/clk/clk.c:2733
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8164ce7b)
Location: drivers/clk/clk.c:2747
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff816ff64d)
Location: drivers/clk/clk.c:2776
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8171c9e6)
Location: drivers/clk/clk.c:2791
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff816fcdc6)
Location: drivers/clk/clk.c:2804
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff81776e40)
Location: drivers/clk/clk.c:2804
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff818ad714)
Location: drivers/clk/clk.c:2821
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_core_set_duty_cycle_parent_nolock(struct clk_core *core, struct clk_duty *duty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f8f10)
Location: drivers/clk/clk.c:3011
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
```
**Symbols:**

```
ffffffff819f8f10-ffffffff819f8f69: clk_core_set_duty_cycle_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_core_set_duty_cycle_parent_nolock(struct clk_core *core, struct clk_duty *duty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a419d0)
Location: drivers/clk/clk.c:3056
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
```
**Symbols:**

```
ffffffff81a419d0-ffffffff81a41a29: clk_core_set_duty_cycle_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_core_set_duty_cycle_parent_nolock(struct clk_core *core, struct clk_duty *duty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8d3e0)
Location: drivers/clk/clk.c:3056
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
```
**Symbols:**

```
ffffffff81a8d3e0-ffffffff81a8d439: clk_core_set_duty_cycle_parent_nolock (STB_LOCAL)
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
In drivers/clk/clk.c (ffff8000107c015c)
Location: drivers/clk/clk.c:2747
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (c08e806c)
Location: drivers/clk/clk.c:2747
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffe00050b8b6)
Location: drivers/clk/clk.c:2747
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff81612edb)
Location: drivers/clk/clk.c:2747
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8160742b)
Location: drivers/clk/clk.c:2747
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff81640cbb)
Location: drivers/clk/clk.c:2747
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8165b3c6)
Location: drivers/clk/clk.c:2747
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
