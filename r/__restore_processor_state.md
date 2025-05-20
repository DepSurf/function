# Function: <code>__restore_processor_state</code>

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
In arch/x86/power/cpu.c (ffffffff816fb073)
Location: arch/x86/power/cpu.c:167
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/power/cpu.c (ffffffff817602d3)
Location: arch/x86/power/cpu.c:193
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/power/cpu.c (ffffffff8178d2d3)
Location: arch/x86/power/cpu.c:193
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/power/cpu.c (ffffffff817ab450)
Location: arch/x86/power/cpu.c:196
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/power/cpu.c (ffffffff81822950)
Location: arch/x86/power/cpu.c:197
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/power/cpu.c (ffffffff8186cb70)
Location: arch/x86/power/cpu.c:197
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/power/cpu.c (ffffffff8188cb80)
Location: arch/x86/power/cpu.c:197
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/power/cpu.c (ffffffff818d7670)
Location: arch/x86/power/cpu.c:197
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff818d7670-ffffffff818d7808: __restore_processor_state.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff819096d0)
Location: arch/x86/power/cpu.c:194
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff819096d0-ffffffff819099d6: __restore_processor_state.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff81bba290)
Location: arch/x86/power/cpu.c:194
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81bba290-ffffffff81bba445: __restore_processor_state.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff81bceb00)
Location: arch/x86/power/cpu.c:194
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81bceb00-ffffffff81bcecb5: __restore_processor_state.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff81bc24b0)
Location: arch/x86/power/cpu.c:191
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81bc24b0-ffffffff81bc2665: __restore_processor_state.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (0)
Location: arch/x86/power/cpu.c:192
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81c92b30-ffffffff81c92d25: __restore_processor_state.constprop.0 (STB_LOCAL)
ffffffff81d44fa1-ffffffff81d44fca: __restore_processor_state.constprop.0.cold (STB_LOCAL)
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
In arch/x86/power/cpu.c (0)
Location: arch/x86/power/cpu.c:194
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81e424a0-ffffffff81e426b1: __restore_processor_state.constprop.0 (STB_LOCAL)
ffffffff81f11e7a-ffffffff81f11ea3: __restore_processor_state.constprop.0.cold (STB_LOCAL)
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
In arch/x86/power/cpu.c (0)
Location: arch/x86/power/cpu.c:195
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8201ce80-ffffffff8201d091: __restore_processor_state.constprop.0 (STB_LOCAL)
ffffffff820b736f-ffffffff820b7398: __restore_processor_state.constprop.0.cold (STB_LOCAL)
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
In arch/x86/power/cpu.c (0)
Location: arch/x86/power/cpu.c:195
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8209d510-ffffffff8209d721: __restore_processor_state.constprop.0 (STB_LOCAL)
ffffffff821386f7-ffffffff82138720: __restore_processor_state.constprop.0.cold (STB_LOCAL)
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
In arch/x86/power/cpu.c (0)
Location: arch/x86/power/cpu.c:195
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff82174d10-ffffffff82174f21: __restore_processor_state.constprop.0 (STB_LOCAL)
ffffffff8221a691-ffffffff8221a6ba: __restore_processor_state.constprop.0.cold (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff818a8a90)
Location: arch/x86/power/cpu.c:194
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff818a8a90-ffffffff818a8d96: __restore_processor_state.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff81863750)
Location: arch/x86/power/cpu.c:194
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/power/cpu.c (ffffffff818fa0f0)
Location: arch/x86/power/cpu.c:194
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff818fa0f0-ffffffff818fa3f6: __restore_processor_state.constprop.0 (STB_LOCAL)
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
In arch/x86/power/cpu.c (ffffffff8191b250)
Location: arch/x86/power/cpu.c:194
Inline: True
Direct callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8191b250-ffffffff8191b556: __restore_processor_state.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
