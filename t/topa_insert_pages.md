# Function: <code>topa_insert_pages</code>

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
In arch/x86/events/intel/pt.c (ffffffff8101441b)
Location: arch/x86/events/intel/pt.c:434
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff81013e69)
Location: arch/x86/events/intel/pt.c:575
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff81013fe9)
Location: arch/x86/events/intel/pt.c:596
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff81012616)
Location: arch/x86/events/intel/pt.c:672
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff810126f1)
Location: arch/x86/events/intel/pt.c:673
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff8101317a)
Location: arch/x86/events/intel/pt.c:673
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff81013b4a)
Location: arch/x86/events/intel/pt.c:681
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff8101501b)
Location: arch/x86/events/intel/pt.c:673
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff81015925)
Location: arch/x86/events/intel/pt.c:701
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff81017170)
Location: arch/x86/events/intel/pt.c:728
Inline: True
```
**Symbols:**

```
ffffffff81017170-ffffffff8101734f: topa_insert_pages.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (ffffffff81017610)
Location: arch/x86/events/intel/pt.c:728
Inline: True
```
**Symbols:**

```
ffffffff81017610-ffffffff810177ef: topa_insert_pages.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (ffffffff81018770)
Location: arch/x86/events/intel/pt.c:728
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
**Symbols:**

```
ffffffff81018770-ffffffff8101894f: topa_insert_pages.constprop.0 (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:728
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
**Symbols:**

```
ffffffff81019b20-ffffffff81019dee: topa_insert_pages.constprop.0 (STB_LOCAL)
ffffffff81c963f9-ffffffff81c96444: topa_insert_pages.constprop.0.cold (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:746
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
**Symbols:**

```
ffffffff8101c040-ffffffff8101c325: topa_insert_pages.constprop.0 (STB_LOCAL)
ffffffff81e45849-ffffffff81e45894: topa_insert_pages.constprop.0.cold (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:746
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
**Symbols:**

```
ffffffff810203a0-ffffffff81020685: topa_insert_pages.constprop.0 (STB_LOCAL)
ffffffff82051096-ffffffff820510e1: topa_insert_pages.constprop.0.cold (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:746
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
**Symbols:**

```
ffffffff810200f0-ffffffff810203d5: topa_insert_pages.constprop.0 (STB_LOCAL)
ffffffff820cf4d1-ffffffff820cf51c: topa_insert_pages.constprop.0.cold (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:747
Inline: True
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
**Symbols:**

```
ffffffff810261e0-ffffffff810264c5: topa_insert_pages.constprop.0 (STB_LOCAL)
ffffffff821a9e3f-ffffffff821a9e8a: topa_insert_pages.constprop.0.cold (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (ffffffff81015925)
Location: arch/x86/events/intel/pt.c:701
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff81014bf5)
Location: arch/x86/events/intel/pt.c:701
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff810158e5)
Location: arch/x86/events/intel/pt.c:701
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
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
In arch/x86/events/intel/pt.c (ffffffff81015b25)
Location: arch/x86/events/intel/pt.c:701
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
</details>
</li>
</ul>

## Differences
