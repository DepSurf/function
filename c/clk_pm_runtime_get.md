# Function: <code>clk_pm_runtime_get</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815abc7d)
Location: drivers/clk/clk.c:93
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
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
In drivers/clk/clk.c (ffffffff815e3c87)
Location: drivers/clk/clk.c:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
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
In drivers/clk/clk.c (ffffffff815fe067)
Location: drivers/clk/clk.c:93
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
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
In drivers/clk/clk.c (ffffffff8162f631)
Location: drivers/clk/clk.c:103
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff8162ce10-ffffffff8162ce2f: clk_pm_runtime_get.isra.0.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816519f1)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff8164e4d0-ffffffff8164e4ef: clk_pm_runtime_get.isra.0.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81700aa1)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff816fcab0-ffffffff816fcb02: clk_pm_runtime_get.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8171dfc1)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff817199f0-ffffffff81719a42: clk_pm_runtime_get.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816fefa1)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff816facf0-ffffffff816fad42: clk_pm_runtime_get.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_pm_runtime_get(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff832f7a43)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff817756e0-ffffffff81775732: clk_pm_runtime_get.part.0 (STB_LOCAL)
ffffffff81777050-ffffffff817770b1: clk_pm_runtime_get (STB_LOCAL)
ffffffff81cf3113-ffffffff81cf3128: clk_pm_runtime_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_pm_runtime_get(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff834b0043)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff818aba20-ffffffff818aba7e: clk_pm_runtime_get.part.0.isra.0 (STB_LOCAL)
ffffffff818ad990-ffffffff818ad9f9: clk_pm_runtime_get (STB_LOCAL)
ffffffff81ebb25f-ffffffff81ebb274: clk_pm_runtime_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_pm_runtime_get(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff83ee988f)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff819f7120-ffffffff819f717e: clk_pm_runtime_get.part.0.isra.0 (STB_LOCAL)
ffffffff819f8f80-ffffffff819f8fe9: clk_pm_runtime_get (STB_LOCAL)
ffffffff82092d5c-ffffffff82092d71: clk_pm_runtime_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_pm_runtime_get(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8370f27f)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff81a3f320-ffffffff81a3f37e: clk_pm_runtime_get.part.0.isra.0 (STB_LOCAL)
ffffffff81a41a40-ffffffff81a41aa9: clk_pm_runtime_get (STB_LOCAL)
ffffffff82113ab0-ffffffff82113ac5: clk_pm_runtime_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_pm_runtime_get(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8e385)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff81a8ac50-ffffffff81a8acae: clk_pm_runtime_get.part.0.isra.0 (STB_LOCAL)
ffffffff81a8d450-ffffffff81a8d4b9: clk_pm_runtime_get (STB_LOCAL)
ffffffff821f1423-ffffffff821f1438: clk_pm_runtime_get.cold (STB_LOCAL)
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
In drivers/clk/clk.c (ffff8000107c2628)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffff8000107bda80-ffff8000107bdab8: clk_pm_runtime_get.isra.0.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (c08ed214)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
c08e94cc-c08e94f4: clk_pm_runtime_get.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffe00051013a)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffe00050cf5a-ffffffe00050cf92: clk_pm_runtime_get.isra.0.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81617a51)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff81614530-ffffffff8161454f: clk_pm_runtime_get.isra.0.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8160bf81)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff81608a60-ffffffff81608a7f: clk_pm_runtime_get.isra.0.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81645831)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff81642310-ffffffff8164232f: clk_pm_runtime_get.isra.0.part.0 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8165fdc1)
Location: drivers/clk/clk.c:109
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff8165c6f0-ffffffff8165c70f: clk_pm_runtime_get.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
