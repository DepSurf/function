# Function: <code>pgd_prepopulate_user_pmd</code>

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
In arch/x86/mm/pgtable.c (ffffffff81082e43)
Location: arch/x86/mm/pgtable.c:329
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff81086a7f)
Location: arch/x86/mm/pgtable.c:313
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8108776f)
Location: arch/x86/mm/pgtable.c:313
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff810898a0)
Location: arch/x86/mm/pgtable.c:320
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff810898a0-ffffffff810898e3: pgd_prepopulate_user_pmd.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pgtable.c (ffffffff81089a70)
Location: arch/x86/mm/pgtable.c:320
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
**Symbols:**

```
ffffffff81089a70-ffffffff81089ab3: pgd_prepopulate_user_pmd.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pgtable.c (ffffffff8108aa7f)
Location: arch/x86/mm/pgtable.c:320
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8109a00c)
Location: arch/x86/mm/pgtable.c:320
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff810ad0b6)
Location: arch/x86/mm/pgtable.c:320
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/x86/mm/pgtable.c (ffffffff8108676f)
Location: arch/x86/mm/pgtable.c:313
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8107547d)
Location: arch/x86/mm/pgtable.c:313
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8108671f)
Location: arch/x86/mm/pgtable.c:313
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
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
In arch/x86/mm/pgtable.c (ffffffff8108885f)
Location: arch/x86/mm/pgtable.c:313
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
</details>
</li>
</ul>

## Differences
