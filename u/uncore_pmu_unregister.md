# Function: <code>uncore_pmu_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015890)
Location: arch/x86/events/intel/uncore.c:755
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff81015a53)
Location: arch/x86/events/intel/uncore.c:765
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff81013f33)
Location: arch/x86/events/intel/uncore.c:765
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff810143c9)
Location: arch/x86/events/intel/uncore.c:765
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff81014f1a)
Location: arch/x86/events/intel/uncore.c:825
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff810159ba)
Location: arch/x86/events/intel/uncore.c:826
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff81016cbe)
Location: arch/x86/events/intel/uncore.c:836
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff8101766e)
Location: arch/x86/events/intel/uncore.c:868
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff810191fe)
Location: arch/x86/events/intel/uncore.c:868
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_types_exit
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
In arch/x86/events/intel/uncore.c (ffffffff8101908e)
Location: arch/x86/events/intel/uncore.c:875
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
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
In arch/x86/events/intel/uncore.c (ffffffff8101a3b8)
Location: arch/x86/events/intel/uncore.c:911
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uncore_pmu_unregister(struct intel_uncore_pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ccd3)
Location: arch/x86/events/intel/uncore.c:918
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_types_exit
```
**Symbols:**

```
ffffffff8101c0a0-ffffffff8101c0db: uncore_pmu_unregister (STB_LOCAL)
ffffffff81c96699-ffffffff81c966ae: uncore_pmu_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uncore_pmu_unregister(struct intel_uncore_pmu *pmu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101f4dd)
Location: arch/x86/events/intel/uncore.c:918
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_types_exit
```
**Symbols:**

```
ffffffff8101e8e0-ffffffff8101e923: uncore_pmu_unregister (STB_LOCAL)
ffffffff81e45b38-ffffffff81e45b4d: uncore_pmu_unregister.cold (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff81023cdd)
Location: arch/x86/events/intel/uncore.c:918
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
  - arch/x86/events/intel/uncore.c:uncore_types_exit
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
In arch/x86/events/intel/uncore.c (ffffffff810239fd)
Location: arch/x86/events/intel/uncore.c:939
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
  - arch/x86/events/intel/uncore.c:uncore_types_exit
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
In arch/x86/events/intel/uncore.c (ffffffff81029b2d)
Location: arch/x86/events/intel/uncore.c:939
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
  - arch/x86/events/intel/uncore.c:uncore_types_exit
  - arch/x86/events/intel/uncore.c:uncore_types_exit
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
In arch/x86/events/intel/uncore.c (ffffffff8101766e)
Location: arch/x86/events/intel/uncore.c:868
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff81016a9e)
Location: arch/x86/events/intel/uncore.c:868
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff8101762e)
Location: arch/x86/events/intel/uncore.c:868
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
In arch/x86/events/intel/uncore.c (ffffffff8101786e)
Location: arch/x86/events/intel/uncore.c:868
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_type_exit
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
</ul>
