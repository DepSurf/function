# Function: <code>clk_core_update_duty_cycle_parent_nolock</code>

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
In drivers/clk/clk.c (ffffffff815f908c)
Location: drivers/clk/clk.c:2551
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8162b1fc)
Location: drivers/clk/clk.c:2691
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8164cd3c)
Location: drivers/clk/clk.c:2705
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff816fbcaf)
Location: drivers/clk/clk.c:2734
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff81718b3f)
Location: drivers/clk/clk.c:2749
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff816f9e3f)
Location: drivers/clk/clk.c:2762
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8177459f)
Location: drivers/clk/clk.c:2762
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff818aa58f)
Location: drivers/clk/clk.c:2779
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_core_update_duty_cycle_parent_nolock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f6180)
Location: drivers/clk/clk.c:2969
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
```
**Symbols:**

```
ffffffff819f6180-ffffffff819f61e2: clk_core_update_duty_cycle_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_core_update_duty_cycle_parent_nolock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3e900)
Location: drivers/clk/clk.c:3014
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
```
**Symbols:**

```
ffffffff81a3e900-ffffffff81a3e962: clk_core_update_duty_cycle_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_core_update_duty_cycle_parent_nolock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8a230)
Location: drivers/clk/clk.c:3014
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
```
**Symbols:**

```
ffffffff81a8a230-ffffffff81a8a292: clk_core_update_duty_cycle_parent_nolock (STB_LOCAL)
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
In drivers/clk/clk.c (ffff8000107bbbe4)
Location: drivers/clk/clk.c:2705
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (c08e7a18)
Location: drivers/clk/clk.c:2705
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffe00050b9b0)
Location: drivers/clk/clk.c:2705
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff81612d9c)
Location: drivers/clk/clk.c:2705
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff816072ec)
Location: drivers/clk/clk.c:2705
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff81640b7c)
Location: drivers/clk/clk.c:2705
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
In drivers/clk/clk.c (ffffffff8165aecc)
Location: drivers/clk/clk.c:2705
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_update_duty_cycle_nolock
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
