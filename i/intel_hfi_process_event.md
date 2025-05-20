# Function: <code>intel_hfi_process_event</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_hfi_process_event(__u64 pkg_therm_status_msr_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b527b0)
Location: drivers/thermal/intel/intel_hfi.c:250
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81b527b0-ffffffff81b5291a: intel_hfi_process_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_hfi_process_event(__u64 pkg_therm_status_msr_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff81cea9a0)
Location: drivers/thermal/intel/intel_hfi.c:248
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81cea9a0-ffffffff81ceab41: intel_hfi_process_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_hfi_process_event(__u64 pkg_therm_status_msr_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d535b0)
Location: drivers/thermal/intel/intel_hfi.c:249
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81d535b0-ffffffff81d53751: intel_hfi_process_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_hfi_process_event(__u64 pkg_therm_status_msr_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a460)
Location: drivers/thermal/intel/intel_hfi.c:252
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
**Symbols:**

```
ffffffff81e0a460-ffffffff81e0a601: intel_hfi_process_event (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
