# Function: <code>clk_core_get_phase</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e5a92)
Location: drivers/clk/clk.c:1903
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_get_phase
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_dump_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174b579)
Location: drivers/clk/clk.c:1932
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_get_phase
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81533df9)
Location: drivers/clk/clk.c:1927
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_get_phase
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815469a9)
Location: drivers/clk/clk.c:1929
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815aa3bc)
Location: drivers/clk/clk.c:2046
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815dfb00)
Location: drivers/clk/clk.c:2374
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff815dfb00-ffffffff815dfb57: clk_core_get_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f9860)
Location: drivers/clk/clk.c:2487
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff815f9860-ffffffff815f98b7: clk_core_get_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162bc10)
Location: drivers/clk/clk.c:2627
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff8162bc10-ffffffff8162bc67: clk_core_get_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164eee0)
Location: drivers/clk/clk.c:2641
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff8164eee0-ffffffff8164ef37: clk_core_get_phase (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81700c3f)
Location: drivers/clk/clk.c:2662
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff8171e15f)
Location: drivers/clk/clk.c:2677
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff816ff12b)
Location: drivers/clk/clk.c:2690
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff817799f6)
Location: drivers/clk/clk.c:2690
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff818afd1f)
Location: drivers/clk/clk.c:2707
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff819fc073)
Location: drivers/clk/clk.c:2897
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81a44b18)
Location: drivers/clk/clk.c:2942
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81a90628)
Location: drivers/clk/clk.c:2942
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bd4d8)
Location: drivers/clk/clk.c:2641
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffff8000107bd4d8-ffff8000107bd53c: clk_core_get_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e9e34)
Location: drivers/clk/clk.c:2641
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
c08e9e34-c08e9e80: clk_core_get_phase (STB_LOCAL)
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
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050c85e)
Location: drivers/clk/clk.c:2641
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffe00050c85e-ffffffe00050c8aa: clk_core_get_phase (STB_LOCAL)
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
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81614f40)
Location: drivers/clk/clk.c:2641
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff81614f40-ffffffff81614f97: clk_core_get_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81609470)
Location: drivers/clk/clk.c:2641
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff81609470-ffffffff816094c7: clk_core_get_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81642d20)
Location: drivers/clk/clk.c:2641
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff81642d20-ffffffff81642d77: clk_core_get_phase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clk_core_get_phase(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165d160)
Location: drivers/clk/clk.c:2641
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_summary_show_subtree
```
**Symbols:**

```
ffffffff8165d160-ffffffff8165d1b7: clk_core_get_phase (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
