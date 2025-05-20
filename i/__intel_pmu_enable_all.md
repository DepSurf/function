# Function: <code>__intel_pmu_enable_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __intel_pmu_enable_all(int added, bool pmi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ae60)
Location: arch/x86/events/intel/core.c:1527
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100ae60-ffffffff8100af08: __intel_pmu_enable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bfc0)
Location: arch/x86/events/intel/core.c:1757
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100bfc0-ffffffff8100c05d: __intel_pmu_enable_all.constprop.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c0a0)
Location: arch/x86/events/intel/core.c:1757
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100c0a0-ffffffff8100c13d: __intel_pmu_enable_all.constprop.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100be30)
Location: arch/x86/events/intel/core.c:1892
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100be30-ffffffff8100beae: __intel_pmu_enable_all.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c2d0)
Location: arch/x86/events/intel/core.c:1892
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100c2d0-ffffffff8100c34e: __intel_pmu_enable_all.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ca20)
Location: arch/x86/events/intel/core.c:1892
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100ca20-ffffffff8100ca9e: __intel_pmu_enable_all.constprop.19 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100cb40)
Location: arch/x86/events/intel/core.c:1896
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100cb40-ffffffff8100cbbe: __intel_pmu_enable_all.constprop.25 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100d380)
Location: arch/x86/events/intel/core.c:1966
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100d380-ffffffff8100d3fe: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100d780)
Location: arch/x86/events/intel/core.c:1967
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100d780-ffffffff8100d7fe: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100e270)
Location: arch/x86/events/intel/core.c:1974
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100e270-ffffffff8100e2e5: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100d440)
Location: arch/x86/events/intel/core.c:1998
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100d440-ffffffff8100d4b5: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100e280)
Location: arch/x86/events/intel/core.c:2163
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100e280-ffffffff8100e31c: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100ea30)
Location: arch/x86/events/intel/core.c:2165
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100ea30-ffffffff8100eac9: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100fcc0)
Location: arch/x86/events/intel/core.c:2186
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack
```
**Symbols:**

```
ffffffff8100fcc0-ffffffff8100fd78: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff81013cf0)
Location: arch/x86/events/intel/core.c:2196
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack
```
**Symbols:**

```
ffffffff81013cf0-ffffffff81013dd2: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff81013550)
Location: arch/x86/events/intel/core.c:2216
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack
```
**Symbols:**

```
ffffffff81013550-ffffffff81013632: __intel_pmu_enable_all.isra.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff81018be0)
Location: arch/x86/events/intel/core.c:2236
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:__intel_pmu_snapshot_branch_stack
```
**Symbols:**

```
ffffffff81018be0-ffffffff81018cc2: __intel_pmu_enable_all.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/events/intel/core.c (ffffffff8100d780)
Location: arch/x86/events/intel/core.c:1967
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100d780-ffffffff8100d7fe: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100c110)
Location: arch/x86/events/intel/core.c:1967
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100c110-ffffffff8100c1a1: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100d740)
Location: arch/x86/events/intel/core.c:1967
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100d740-ffffffff8100d7be: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100d910)
Location: arch/x86/events/intel/core.c:1967
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100d910-ffffffff8100d98e: __intel_pmu_enable_all.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
