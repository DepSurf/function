# Function: <code>intel_hfi_init</code>

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
void intel_hfi_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff834bfeda)
Location: drivers/thermal/intel/intel_hfi.c:526
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
**Symbols:**

```
ffffffff834bfeda-ffffffff834c0080: intel_hfi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_hfi_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efeca0)
Location: drivers/thermal/intel/intel_hfi.c:534
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
**Symbols:**

```
ffffffff83efeca0-ffffffff83efee2d: intel_hfi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_hfi_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724b10)
Location: drivers/thermal/intel/intel_hfi.c:535
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
**Symbols:**

```
ffffffff83724b10-ffffffff83724c9c: intel_hfi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_hfi_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff83958980)
Location: drivers/thermal/intel/intel_hfi.c:600
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
**Symbols:**

```
ffffffff83958980-ffffffff83958b14: intel_hfi_init (STB_GLOBAL)
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
