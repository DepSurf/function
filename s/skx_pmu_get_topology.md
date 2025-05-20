# Function: <code>skx_pmu_get_topology</code>

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
int skx_pmu_get_topology(struct intel_uncore_type *type, int (*topology_cb)(struct intel_uncore_type *, int, int, u64));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102db20)
Location: arch/x86/events/intel/uncore_snbep.c:3860
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_get_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
```
**Symbols:**

```
ffffffff8102db20-ffffffff8102dc7a: skx_pmu_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skx_pmu_get_topology(struct intel_uncore_type *type, int (*topology_cb)(struct intel_uncore_type *, int, int, u64));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c8c0)
Location: arch/x86/events/intel/uncore_snbep.c:3850
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_get_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
```
**Symbols:**

```
ffffffff8102c8c0-ffffffff8102ca1a: skx_pmu_get_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skx_pmu_get_topology(struct intel_uncore_type *type, int (*topology_cb)(struct intel_uncore_type *, int, int, u64));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032a20)
Location: arch/x86/events/intel/uncore_snbep.c:3858
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_get_topology
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology
```
**Symbols:**

```
ffffffff81032a20-ffffffff81032b77: skx_pmu_get_topology (STB_LOCAL)
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
