# Function: <code>sad_cfg_iio_topology</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sad_cfg_iio_topology(struct intel_uncore_type *type, u8 *sad_pmon_mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024110)
Location: arch/x86/events/intel/uncore_snbep.c:4458
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_get_topology
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_get_topology
```
**Symbols:**

```
ffffffff81024110-ffffffff810242af: sad_cfg_iio_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sad_cfg_iio_topology(struct intel_uncore_type *type, u8 *sad_pmon_mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810281d0)
Location: arch/x86/events/intel/uncore_snbep.c:4458
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_get_topology
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_get_topology
```
**Symbols:**

```
ffffffff810281d0-ffffffff8102835b: sad_cfg_iio_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sad_cfg_iio_topology(struct intel_uncore_type *type, u8 *sad_pmon_mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c9b0)
Location: arch/x86/events/intel/uncore_snbep.c:4719
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_get_topology
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_get_topology
```
**Symbols:**

```
ffffffff8102c9b0-ffffffff8102cb02: sad_cfg_iio_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sad_cfg_iio_topology(struct intel_uncore_type *type, u8 *sad_pmon_mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102cbf0)
Location: arch/x86/events/intel/uncore_snbep.c:4709
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_get_topology
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_get_topology
```
**Symbols:**

```
ffffffff8102cbf0-ffffffff8102cd42: sad_cfg_iio_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sad_cfg_iio_topology(struct intel_uncore_type *type, u8 *sad_pmon_mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032d50)
Location: arch/x86/events/intel/uncore_snbep.c:4717
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_iio_get_topology
  - arch/x86/events/intel/uncore_snbep.c:snr_iio_get_topology
```
**Symbols:**

```
ffffffff81032d50-ffffffff81032ea2: sad_cfg_iio_topology (STB_LOCAL)
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
