# Function: <code>e820_search_gap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int e820_search_gap(long unsigned int *gapstart, long unsigned int *gapsize, long unsigned int start_addr, long long unsigned int end_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f67f70)
Location: arch/x86/kernel/e820.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_setup_gap
```
**Symbols:**

```
ffffffff81f67f70-ffffffff81f67fe2: e820_search_gap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int e820_search_gap(long unsigned int *gapstart, long unsigned int *gapsize, long unsigned int start_addr, long long unsigned int end_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f8fe25)
Location: arch/x86/kernel/e820.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_setup_gap
```
**Symbols:**

```
ffffffff81f8fe25-ffffffff81f8feab: e820_search_gap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int e820_search_gap(long unsigned int *gapstart, long unsigned int *gapsize, long unsigned int start_addr, long long unsigned int end_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81fcb1f7)
Location: arch/x86/kernel/e820.c:585
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_setup_gap
```
**Symbols:**

```
ffffffff81fcb1f7-ffffffff81fcb270: e820_search_gap (STB_GLOBAL)
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
In arch/x86/kernel/e820.c (ffffffff820ab9db)
Location: arch/x86/kernel/e820.c:571
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff826b21b1)
Location: arch/x86/kernel/e820.c:591
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff826db879)
Location: arch/x86/kernel/e820.c:593
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff82891c60)
Location: arch/x86/kernel/e820.c:592
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff828a91be)
Location: arch/x86/kernel/e820.c:606
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff828ac222)
Location: arch/x86/kernel/e820.c:606
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff82cd1750)
Location: arch/x86/kernel/e820.c:607
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff82fbd5a0)
Location: arch/x86/kernel/e820.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff831c7cb4)
Location: arch/x86/kernel/e820.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff832a8e9b)
Location: arch/x86/kernel/e820.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff834584fb)
Location: arch/x86/kernel/e820.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff83e777e5)
Location: arch/x86/kernel/e820.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff83699be5)
Location: arch/x86/kernel/e820.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff838c9965)
Location: arch/x86/kernel/e820.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff8289a234)
Location: arch/x86/kernel/e820.c:606
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff828924f2)
Location: arch/x86/kernel/e820.c:606
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff828ad214)
Location: arch/x86/kernel/e820.c:606
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
In arch/x86/kernel/e820.c (ffffffff828ad232)
Location: arch/x86/kernel/e820.c:606
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__setup_pci_gap
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
</ul>
