# Function: <code>clk_core_determine_round_nolock</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e0d11)
Location: drivers/clk/clk.c:1068
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff815e0650-ffffffff815e06a3: clk_core_determine_round_nolock.part.16 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff815fab61)
Location: drivers/clk/clk.c:1174
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff815fa680-ffffffff815fa6d3: clk_core_determine_round_nolock.part.15 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8162d1a2)
Location: drivers/clk/clk.c:1295
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8162c8e0-ffffffff8162c937: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8164e862)
Location: drivers/clk/clk.c:1303
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8164ddb0-ffffffff8164de07: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816fde02)
Location: drivers/clk/clk.c:1307
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff816fca00-ffffffff816fca5b: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8171afe2)
Location: drivers/clk/clk.c:1301
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81719940-ffffffff8171999b: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816fc0b2)
Location: drivers/clk/clk.c:1322
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff816fac40-ffffffff816fac9b: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81777e7f)
Location: drivers/clk/clk.c:1322
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81775100-ffffffff8177515b: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_core_determine_round_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818a9ed0)
Location: drivers/clk/clk.c:1334
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
**Symbols:**

```
ffffffff818a9ed0-ffffffff818a9f84: clk_core_determine_round_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_core_determine_round_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f59c0)
Location: drivers/clk/clk.c:1418
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
**Symbols:**

```
ffffffff819f59c0-ffffffff819f5ab5: clk_core_determine_round_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_core_determine_round_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3e140)
Location: drivers/clk/clk.c:1462
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
**Symbols:**

```
ffffffff81a3e140-ffffffff81a3e235: clk_core_determine_round_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_core_determine_round_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a89a30)
Location: drivers/clk/clk.c:1462
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
**Symbols:**

```
ffffffff81a89a30-ffffffff81a89b25: clk_core_determine_round_nolock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bdd60)
Location: drivers/clk/clk.c:1303
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffff8000107bcba0-ffff8000107bcc1c: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (c08e975c)
Location: drivers/clk/clk.c:1303
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
c08e8e5c-c08e8ec4: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050d306)
Location: drivers/clk/clk.c:1303
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffe00050bf6a-ffffffe00050bfd4: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
```
</details>
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
In drivers/clk/clk.c (ffffffff816148c2)
Location: drivers/clk/clk.c:1303
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81613e10-ffffffff81613e67: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81608df2)
Location: drivers/clk/clk.c:1303
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81608340-ffffffff81608397: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816426a2)
Location: drivers/clk/clk.c:1303
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81641bf0-ffffffff81641c47: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8165cab2)
Location: drivers/clk/clk.c:1303
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8165bfd0-ffffffff8165c027: clk_core_determine_round_nolock.part.0 (STB_LOCAL)
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
