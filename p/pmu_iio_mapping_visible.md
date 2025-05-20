# Function: <code>pmu_iio_mapping_visible</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023b37)
Location: arch/x86/events/intel/uncore_snbep.c:3709
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff810279d7)
Location: arch/x86/events/intel/uncore_snbep.c:3709
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t pmu_iio_mapping_visible(struct kobject *kobj, struct attribute *attr, int die, int zero_bus_pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e130)
Location: arch/x86/events/intel/uncore_snbep.c:3735
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible
```
**Symbols:**

```
ffffffff8102e130-ffffffff8102e1ab: pmu_iio_mapping_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t pmu_iio_mapping_visible(struct kobject *kobj, struct attribute *attr, int die, int zero_bus_pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e110)
Location: arch/x86/events/intel/uncore_snbep.c:3725
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible
```
**Symbols:**

```
ffffffff8102e110-ffffffff8102e18b: pmu_iio_mapping_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
umode_t pmu_iio_mapping_visible(struct kobject *kobj, struct attribute *attr, int die, int zero_bus_pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81033ed0)
Location: arch/x86/events/intel/uncore_snbep.c:3733
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_mapping_visible
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_visible
```
**Symbols:**

```
ffffffff81033ed0-ffffffff81033f4b: pmu_iio_mapping_visible (STB_LOCAL)
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
