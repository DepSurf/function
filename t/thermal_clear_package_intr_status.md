# Function: <code>thermal_clear_package_intr_status</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void thermal_clear_package_intr_status(int level, u64 bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9bbe)
Location: drivers/thermal/intel/therm_throt.c:203
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
**Symbols:**

```
ffffffff81ce9ab0-ffffffff81ce9b17: thermal_clear_package_intr_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void thermal_clear_package_intr_status(int level, u64 bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52773)
Location: drivers/thermal/intel/therm_throt.c:262
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
**Symbols:**

```
ffffffff81d525f0-ffffffff81d52648: thermal_clear_package_intr_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void thermal_clear_package_intr_status(int level, u64 bit_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (ffffffff81e094d3)
Location: drivers/thermal/intel/therm_throt.c:262
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
**Symbols:**

```
ffffffff81e09350-ffffffff81e093a8: thermal_clear_package_intr_status (STB_GLOBAL)
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
