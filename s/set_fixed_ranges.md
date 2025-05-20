# Function: <code>set_fixed_ranges</code>

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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c33f)
Location: arch/x86/kernel/cpu/mtrr/generic.c:633
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c408)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e858)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e7b4)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81052124)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054df4)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810524b4)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055596)
Location: arch/x86/kernel/cpu/mtrr/generic.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055e96)
Location: arch/x86/kernel/cpu/mtrr/generic.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:637
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
```
**Symbols:**

```
ffffffff8105aff0-ffffffff8105b0ab: set_fixed_ranges.constprop.0 (STB_LOCAL)
ffffffff8105b2ca-ffffffff8105b2fb: set_fixed_ranges.constprop.0.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:637
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
```
**Symbols:**

```
ffffffff81059b50-ffffffff81059c0b: set_fixed_ranges.constprop.0 (STB_LOCAL)
ffffffff81bd5e4d-ffffffff81bd5e7e: set_fixed_ranges.constprop.0.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a5af)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81063a42)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81070729)
Location: arch/x86/kernel/cpu/mtrr/generic.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81080919)
Location: arch/x86/kernel/cpu/mtrr/generic.c:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81082d78)
Location: arch/x86/kernel/cpu/mtrr/generic.c:854
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8108a888)
Location: arch/x86/kernel/cpu/mtrr/generic.c:860
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055a16)
Location: arch/x86/kernel/cpu/mtrr/generic.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81045b42)
Location: arch/x86/kernel/cpu/mtrr/generic.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055e46)
Location: arch/x86/kernel/cpu/mtrr/generic.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810572e6)
Location: arch/x86/kernel/cpu/mtrr/generic.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
```
</details>
</li>
</ul>

## Differences
