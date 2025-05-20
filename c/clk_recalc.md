# Function: <code>clk_recalc</code>

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
In drivers/clk/clk.c (ffffffff816e4736)
Location: drivers/clk/clk.c:987
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_recalc_rates
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:clk_change_rate
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
In drivers/clk/clk.c (ffffffff8174c037)
Location: drivers/clk/clk.c:1036
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
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
In drivers/clk/clk.c (ffffffff81534897)
Location: drivers/clk/clk.c:1036
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
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
In drivers/clk/clk.c (ffffffff81547b15)
Location: drivers/clk/clk.c:1038
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a8f60)
Location: drivers/clk/clk.c:1111
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff815a8f60-ffffffff815a8fca: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e0910)
Location: drivers/clk/clk.c:1320
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff815e0910-ffffffff815e097b: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fa9f0)
Location: drivers/clk/clk.c:1426
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff815fa9f0-ffffffff815faa5b: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162d030)
Location: drivers/clk/clk.c:1544
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff8162d030-ffffffff8162d09f: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164e6f0)
Location: drivers/clk/clk.c:1552
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff8164e6f0-ffffffff8164e75f: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fdc90)
Location: drivers/clk/clk.c:1556
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff816fdc90-ffffffff816fdcfb: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171ae70)
Location: drivers/clk/clk.c:1565
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff8171ae70-ffffffff8171aedb: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fbf40)
Location: drivers/clk/clk.c:1586
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff816fbf40-ffffffff816fbfab: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81777d18)
Location: drivers/clk/clk.c:1586
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81777cf0-ffffffff81777d66: clk_recalc (STB_LOCAL)
ffffffff81cf3158-ffffffff81cf316d: clk_recalc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff818adfe8)
Location: drivers/clk/clk.c:1600
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff818adfc0-ffffffff818ae04a: clk_recalc (STB_LOCAL)
ffffffff81ebb2a4-ffffffff81ebb2b9: clk_recalc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f99a8)
Location: drivers/clk/clk.c:1775
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff819f9980-ffffffff819f9a0a: clk_recalc (STB_LOCAL)
ffffffff82092da1-ffffffff82092db6: clk_recalc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a42058)
Location: drivers/clk/clk.c:1820
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81a42030-ffffffff81a420ba: clk_recalc (STB_LOCAL)
ffffffff82113af5-ffffffff82113b0a: clk_recalc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8da68)
Location: drivers/clk/clk.c:1820
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81a8da40-ffffffff81a8daca: clk_recalc (STB_LOCAL)
ffffffff821f1468-ffffffff821f147d: clk_recalc.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bdba8)
Location: drivers/clk/clk.c:1552
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffff8000107bdba8-ffff8000107bdc48: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e95d0)
Location: drivers/clk/clk.c:1552
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
c08e95d0-c08e9654: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050d198)
Location: drivers/clk/clk.c:1552
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffe00050d198-ffffffe00050d21e: clk_recalc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81614750)
Location: drivers/clk/clk.c:1552
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81614750-ffffffff816147bf: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81608c80)
Location: drivers/clk/clk.c:1552
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81608c80-ffffffff81608cef: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81642530)
Location: drivers/clk/clk.c:1552
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81642530-ffffffff8164259f: clk_recalc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_recalc(struct clk_core *core, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165c940)
Location: drivers/clk/clk.c:1552
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_subtree
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff8165c940-ffffffff8165c9af: clk_recalc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
