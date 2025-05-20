# Function: <code>upi_fill_topology</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int upi_fill_topology(struct pci_dev *dev, struct intel_uncore_topology *tp, int pmu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102bea0)
Location: arch/x86/events/intel/uncore_snbep.c:4312
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
```
**Symbols:**

```
ffffffff8102bea0-ffffffff8102bf6f: upi_fill_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int upi_fill_topology(struct pci_dev *dev, struct intel_uncore_topology *tp, int pmu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102bed0)
Location: arch/x86/events/intel/uncore_snbep.c:4302
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
```
**Symbols:**

```
ffffffff8102bed0-ffffffff8102bf9f: upi_fill_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int upi_fill_topology(struct pci_dev *dev, struct intel_uncore_topology *tp, int pmu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032030)
Location: arch/x86/events/intel/uncore_snbep.c:4310
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_topology_cb
```
**Symbols:**

```
ffffffff81032030-ffffffff810320ff: upi_fill_topology (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
