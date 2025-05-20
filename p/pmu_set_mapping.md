# Function: <code>pmu_set_mapping</code>

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
void pmu_set_mapping(struct intel_uncore_type *type, struct attribute_group *ag, ssize_t (*show)(struct device *, struct device_attribute *, char *), int topology_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102eb20)
Location: arch/x86/events/intel/uncore_snbep.c:3929
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:icx_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
```
**Symbols:**

```
ffffffff8102eb20-ffffffff8102ef3e: pmu_set_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmu_set_mapping(struct intel_uncore_type *type, struct attribute_group *ag, ssize_t (*show)(struct device *, struct device_attribute *, char *), int topology_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102ee10)
Location: arch/x86/events/intel/uncore_snbep.c:3919
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:icx_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
```
**Symbols:**

```
ffffffff8102ee10-ffffffff8102f1af: pmu_set_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pmu_set_mapping(struct intel_uncore_type *type, struct attribute_group *ag, ssize_t (*show)(struct device *, struct device_attribute *, char *), int topology_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81034a50)
Location: arch/x86/events/intel/uncore_snbep.c:3927
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:icx_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_set_mapping
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
```
**Symbols:**

```
ffffffff81034a50-ffffffff81034def: pmu_set_mapping (STB_LOCAL)
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
