# Function: <code>pti_clone_pgtable</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pti.c (ffffffff8108a080)
Location: arch/x86/mm/pti.c:310
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108a080-ffffffff8108a1e7: pti_clone_pgtable.constprop.9 (STB_LOCAL)
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:304
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108de20-ffffffff8108df52: pti_clone_pgtable.constprop.0 (STB_LOCAL)
ffffffff8108e183-ffffffff8108e1bc: pti_clone_pgtable.constprop.0.cold (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff8108ea90)
Location: arch/x86/mm/pti.c:304
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108ea90-ffffffff8108ec08: pti_clone_pgtable.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff81094de0)
Location: arch/x86/mm/pti.c:304
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_kernel_text
```
**Symbols:**

```
ffffffff81094de0-ffffffff81094fb5: pti_clone_pgtable.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff810941a0)
Location: arch/x86/mm/pti.c:303
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_kernel_text
```
**Symbols:**

```
ffffffff810941a0-ffffffff81094375: pti_clone_pgtable.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff81094b40)
Location: arch/x86/mm/pti.c:303
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff81094b40-ffffffff81094ce6: pti_clone_pgtable.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:303
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810a4ab0-ffffffff810a4c70: pti_clone_pgtable.constprop.0 (STB_LOCAL)
ffffffff81ca24ba-ffffffff81ca24d6: pti_clone_pgtable.constprop.0.cold (STB_LOCAL)
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:303
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810b9350-ffffffff810b953f: pti_clone_pgtable.constprop.0 (STB_LOCAL)
ffffffff81e51bb7-ffffffff81e51bd3: pti_clone_pgtable.constprop.0.cold (STB_LOCAL)
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:303
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810d4e90-ffffffff810d508e: pti_clone_pgtable.constprop.0 (STB_LOCAL)
ffffffff820553ce-ffffffff820553ea: pti_clone_pgtable.constprop.0.cold (STB_LOCAL)
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:303
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810d8390-ffffffff810d858e: pti_clone_pgtable.constprop.0 (STB_LOCAL)
ffffffff820d3999-ffffffff820d39b5: pti_clone_pgtable.constprop.0.cold (STB_LOCAL)
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/mm/pti.c:303
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff810e0c10-ffffffff810e0e0e: pti_clone_pgtable.constprop.0 (STB_LOCAL)
ffffffff821ae807-ffffffff821ae823: pti_clone_pgtable.constprop.0.cold (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff8108da50)
Location: arch/x86/mm/pti.c:304
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108da50-ffffffff8108dbc8: pti_clone_pgtable.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff8107c5a0)
Location: arch/x86/mm/pti.c:304
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8107c5a0-ffffffff8107c6ed: pti_clone_pgtable.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff8108da00)
Location: arch/x86/mm/pti.c:304
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108da00-ffffffff8108db78: pti_clone_pgtable.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/pti.c (ffffffff8108fde0)
Location: arch/x86/mm/pti.c:304
Inline: True
Direct callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8108fde0-ffffffff8108ff58: pti_clone_pgtable.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
