# Function: <code>uncore_pci_pmu_unregister</code>

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
void uncore_pci_pmu_unregister(struct intel_uncore_pmu *pmu, int phys_id, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019010)
Location: arch/x86/events/intel/uncore.c:1148
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
**Symbols:**

```
ffffffff81019010-ffffffff810190b5: uncore_pci_pmu_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101a340)
Location: arch/x86/events/intel/uncore.c:1208
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
**Symbols:**

```
ffffffff8101a340-ffffffff8101a3d7: uncore_pci_pmu_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:1215
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
**Symbols:**

```
ffffffff8101cc50-ffffffff8101ccf4: uncore_pci_pmu_unregister (STB_LOCAL)
ffffffff81c96831-ffffffff81c96846: uncore_pci_pmu_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:1215
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
**Symbols:**

```
ffffffff8101f450-ffffffff8101f4fe: uncore_pci_pmu_unregister (STB_LOCAL)
ffffffff81e45ce8-ffffffff81e45cfd: uncore_pci_pmu_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:1215
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
**Symbols:**

```
ffffffff81023c50-ffffffff81023cfe: uncore_pci_pmu_unregister (STB_LOCAL)
ffffffff8205132b-ffffffff82051340: uncore_pci_pmu_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:1236
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
**Symbols:**

```
ffffffff81023970-ffffffff81023a1e: uncore_pci_pmu_unregister (STB_LOCAL)
ffffffff820cf75d-ffffffff820cf772: uncore_pci_pmu_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void uncore_pci_pmu_unregister(struct intel_uncore_pmu *pmu, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:1236
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
**Symbols:**

```
ffffffff81029aa0-ffffffff81029b4e: uncore_pci_pmu_unregister (STB_LOCAL)
ffffffff821aa0cb-ffffffff821aa0e0: uncore_pci_pmu_unregister.cold (STB_LOCAL)
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
<code>pmu, phys_id, die</code> ➡️ <code>pmu, die</code>
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
