# Function: <code>clk_core_set_phase_nolock</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815df98c)
Location: drivers/clk/clk.c:2301
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f96ec)
Location: drivers/clk/clk.c:2414
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffff8162baa1)
Location: drivers/clk/clk.c:2554
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffff8164ed71)
Location: drivers/clk/clk.c:2568
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clk_core_set_phase_nolock(struct clk_core *core, int degrees);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ff430)
Location: drivers/clk/clk.c:2589
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_set_phase
```
**Symbols:**

```
ffffffff816ff430-ffffffff816ff54e: clk_core_set_phase_nolock (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8171d4b8)
Location: drivers/clk/clk.c:2604
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffff816fe548)
Location: drivers/clk/clk.c:2617
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffff81778d38)
Location: drivers/clk/clk.c:2617
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_core_set_phase_nolock(struct clk_core *core, int degrees);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818ad4e0)
Location: drivers/clk/clk.c:2634
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_set_phase
```
**Symbols:**

```
ffffffff818ad4e0-ffffffff818ad60c: clk_core_set_phase_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_core_set_phase_nolock(struct clk_core *core, int degrees);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f8c90)
Location: drivers/clk/clk.c:2824
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_set_phase
```
**Symbols:**

```
ffffffff819f8c90-ffffffff819f8dbc: clk_core_set_phase_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_core_set_phase_nolock(struct clk_core *core, int degrees);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a414a0)
Location: drivers/clk/clk.c:2869
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_set_phase
```
**Symbols:**

```
ffffffff81a414a0-ffffffff81a415cc: clk_core_set_phase_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_core_set_phase_nolock(struct clk_core *core, int degrees);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8ceb0)
Location: drivers/clk/clk.c:2869
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_set_phase
```
**Symbols:**

```
ffffffff81a8ceb0-ffffffff81a8cfdc: clk_core_set_phase_nolock (STB_LOCAL)
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
In drivers/clk/clk.c (ffff8000107c02e8)
Location: drivers/clk/clk.c:2568
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (c08e9c98)
Location: drivers/clk/clk.c:2568
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffe00050c8f0)
Location: drivers/clk/clk.c:2568
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffff81614dd1)
Location: drivers/clk/clk.c:2568
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffff81609301)
Location: drivers/clk/clk.c:2568
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffff81642bb1)
Location: drivers/clk/clk.c:2568
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
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
In drivers/clk/clk.c (ffffffff8165cfc1)
Location: drivers/clk/clk.c:2568
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
