# Function: <code>cbm_ensure_valid</code>

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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059da4)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2448
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b3ac)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2490
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bcbc)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2496
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061950)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2595
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fd5e)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2626
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810602e8)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106946f)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2673
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810766d3)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2673
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81086280)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2716
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
**Symbols:**

```
ffffffff81086280-ffffffff81086303: cbm_ensure_valid.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088eb0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2998
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
**Symbols:**

```
ffffffff81088eb0-ffffffff81088f33: cbm_ensure_valid.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108fd30)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:3126
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
```
**Symbols:**

```
ffffffff8108fd30-ffffffff8108fdb3: cbm_ensure_valid.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b83c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2496
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104ba0c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2496
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bc6c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2496
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d15c)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2496
Inline: True
```
</details>
</li>
</ul>

## Differences
