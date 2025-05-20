# Function: <code>uncore_pci_exit</code>

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
In arch/x86/events/intel/uncore.c (ffffffff81f60258)
Location: arch/x86/events/intel/uncore.c:1021
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff820e6f0b)
Location: arch/x86/events/intel/uncore.c:1046
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8107e37b-ffffffff8107e3c6: uncore_pci_exit.part.23 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff821ccdfe)
Location: arch/x86/events/intel/uncore.c:1032
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8108291b-ffffffff81082966: uncore_pci_exit.part.23 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff822c1f06)
Location: arch/x86/events/intel/uncore.c:1032
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81014acd-ffffffff81014b18: uncore_pci_exit.part.23 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff828d5086)
Location: arch/x86/events/intel/uncore.c:1040
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8101532d-ffffffff81015378: uncore_pci_exit.part.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void uncore_pci_exit();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015f1d)
Location: arch/x86/events/intel/uncore.c:1101
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81015f1d-ffffffff81015f72: uncore_pci_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void uncore_pci_exit();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101669d)
Location: arch/x86/events/intel/uncore.c:1102
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8101669d-ffffffff810166f2: uncore_pci_exit (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82b03770)
Location: arch/x86/events/intel/uncore.c:1114
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81017cce-ffffffff81017d19: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82b12660)
Location: arch/x86/events/intel/uncore.c:1146
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8101865e-ffffffff810186a9: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82f240fb)
Location: arch/x86/events/intel/uncore.c:1146
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81019fc8-ffffffff8101a003: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff8321c69b)
Location: arch/x86/events/intel/uncore.c:1304
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81bd2438-ffffffff81bd2490: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff83450693)
Location: arch/x86/events/intel/uncore.c:1412
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81bc4742-ffffffff81bc47b4: uncore_pci_exit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void uncore_pci_exit();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81c9678e)
Location: arch/x86/events/intel/uncore.c:1419
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81c9678e-ffffffff81c96821: uncore_pci_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void uncore_pci_exit();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81e45c33)
Location: arch/x86/events/intel/uncore.c:1419
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81e45c33-ffffffff81e45cd0: uncore_pci_exit (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff842af41c)
Location: arch/x86/events/intel/uncore.c:1419
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81023b60-ffffffff81023c31: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff83af1e8c)
Location: arch/x86/events/intel/uncore.c:1440
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81023880-ffffffff81023951: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff83d4dbac)
Location: arch/x86/events/intel/uncore.c:1440
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff810299b0-ffffffff81029a81: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82af2880)
Location: arch/x86/events/intel/uncore.c:1146
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8101865e-ffffffff810186a9: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82ac2ca8)
Location: arch/x86/events/intel/uncore.c:1146
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81017a8e-ffffffff81017ad9: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82b0d948)
Location: arch/x86/events/intel/uncore.c:1146
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8101861e-ffffffff81018669: uncore_pci_exit.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82b02498)
Location: arch/x86/events/intel/uncore.c:1146
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8101885e-ffffffff810188a9: uncore_pci_exit.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
