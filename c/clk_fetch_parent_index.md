# Function: <code>clk_fetch_parent_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int clk_fetch_parent_index(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e62c0)
Location: drivers/clk/clk.c:1065
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_core_set_parent
```
**Symbols:**

```
ffffffff816e62c0-ffffffff816e639f: clk_fetch_parent_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_fetch_parent_index(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81749bb0)
Location: drivers/clk/clk.c:1114
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81749bb0-ffffffff81749c06: clk_fetch_parent_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_fetch_parent_index(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81532430)
Location: drivers/clk/clk.c:1114
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81532430-ffffffff81532486: clk_fetch_parent_index (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81545aa2)
Location: drivers/clk/clk.c:1116
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
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
In drivers/clk/clk.c (ffffffff815a9425)
Location: drivers/clk/clk.c:1193
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e0e13)
Location: drivers/clk/clk.c:1402
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
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
In drivers/clk/clk.c (ffffffff815fac8d)
Location: drivers/clk/clk.c:1508
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff815fa8c0-ffffffff815fa964: clk_fetch_parent_index.part.20 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8162d2e3)
Location: drivers/clk/clk.c:1626
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8162cd00-ffffffff8162cdbe: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8164e9a3)
Location: drivers/clk/clk.c:1634
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8164e1c0-ffffffff8164e27e: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816fdf4f)
Location: drivers/clk/clk.c:1637
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
```
**Symbols:**

```
ffffffff816fce80-ffffffff816fcf42: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8171b12f)
Location: drivers/clk/clk.c:1646
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
```
**Symbols:**

```
ffffffff81719dc0-ffffffff81719e82: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816fc210)
Location: drivers/clk/clk.c:1667
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
```
**Symbols:**

```
ffffffff816fb0c0-ffffffff816fb182: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81777fe7)
Location: drivers/clk/clk.c:1667
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
```
**Symbols:**

```
ffffffff81775840-ffffffff81775902: clk_fetch_parent_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_fetch_parent_index(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818abcd0)
Location: drivers/clk/clk.c:1681
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
```
**Symbols:**

```
ffffffff818abcd0-ffffffff818abda4: clk_fetch_parent_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_fetch_parent_index(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f7390)
Location: drivers/clk/clk.c:1861
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
```
**Symbols:**

```
ffffffff819f7390-ffffffff819f7464: clk_fetch_parent_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_fetch_parent_index(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3f4b0)
Location: drivers/clk/clk.c:1906
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
```
**Symbols:**

```
ffffffff81a3f4b0-ffffffff81a3f585: clk_fetch_parent_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_fetch_parent_index(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8ade0)
Location: drivers/clk/clk.c:1906
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_index
```
**Symbols:**

```
ffffffff81a8ade0-ffffffff81a8aeb5: clk_fetch_parent_index (STB_LOCAL)
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
In drivers/clk/clk.c (ffff8000107bdee8)
Location: drivers/clk/clk.c:1634
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffff8000107bd2b8-ffff8000107bd3c0: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (c08e98ec)
Location: drivers/clk/clk.c:1634
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
c08e9368-c08e9458: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffe00050d452)
Location: drivers/clk/clk.c:1634
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffe00050c6a2-ffffffe00050c75c: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81614a03)
Location: drivers/clk/clk.c:1634
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81614220-ffffffff816142de: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81608f33)
Location: drivers/clk/clk.c:1634
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81608750-ffffffff8160880e: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816427e3)
Location: drivers/clk/clk.c:1634
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81642000-ffffffff816420be: clk_fetch_parent_index.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8165cbf3)
Location: drivers/clk/clk.c:1634
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8165c3e0-ffffffff8165c49e: clk_fetch_parent_index.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
