# Function: <code>uncore_pci_pmu_register</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uncore_pci_pmu_register(struct pci_dev *pdev, struct intel_uncore_type *type, struct intel_uncore_pmu *pmu, int phys_id, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81018620)
Location: arch/x86/events/intel/uncore.c:1052
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_driver_init
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
**Symbols:**

```
ffffffff81018620-ffffffff810187b1: uncore_pci_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uncore_pci_pmu_register(struct pci_dev *pdev, struct intel_uncore_type *type, struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019950)
Location: arch/x86/events/intel/uncore.c:1114
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
**Symbols:**

```
ffffffff81019950-ffffffff81019ad4: uncore_pci_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uncore_pci_pmu_register(struct pci_dev *pdev, struct intel_uncore_type *type, struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101e670)
Location: arch/x86/events/intel/uncore.c:1121
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
**Symbols:**

```
ffffffff8101e670-ffffffff8101e7f4: uncore_pci_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uncore_pci_pmu_register(struct pci_dev *pdev, struct intel_uncore_type *type, struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810211a0)
Location: arch/x86/events/intel/uncore.c:1121
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
**Symbols:**

```
ffffffff810211a0-ffffffff81021347: uncore_pci_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uncore_pci_pmu_register(struct pci_dev *pdev, struct intel_uncore_type *type, struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81025b80)
Location: arch/x86/events/intel/uncore.c:1121
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
**Symbols:**

```
ffffffff81025b80-ffffffff81025d27: uncore_pci_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uncore_pci_pmu_register(struct pci_dev *pdev, struct intel_uncore_type *type, struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81025aa0)
Location: arch/x86/events/intel/uncore.c:1142
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
**Symbols:**

```
ffffffff81025aa0-ffffffff81025c47: uncore_pci_pmu_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uncore_pci_pmu_register(struct pci_dev *pdev, struct intel_uncore_type *type, struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8102bc00)
Location: arch/x86/events/intel/uncore.c:1142
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
**Symbols:**

```
ffffffff8102bc00-ffffffff8102bda7: uncore_pci_pmu_register (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int phys_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>pdev, type, pmu, phys_id, die</code> ➡️ <code>pdev, type, pmu, die</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
