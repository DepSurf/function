# Function: <code>intel_hfi_online</code>

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
void intel_hfi_online(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52920)
Location: drivers/thermal/intel/intel_hfi.c:354
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81b52920-ffffffff81b52bc6: intel_hfi_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_hfi_online(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff81ceab60)
Location: drivers/thermal/intel/intel_hfi.c:362
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81ceab60-ffffffff81ceae0a: intel_hfi_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_hfi_online(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d53770)
Location: drivers/thermal/intel/intel_hfi.c:363
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81d53770-ffffffff81d53a1a: intel_hfi_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_hfi_online(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a620)
Location: drivers/thermal/intel/intel_hfi.c:412
Inline: False
Direct callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_online
```
**Symbols:**

```
ffffffff81e0a620-ffffffff81e0a8d4: intel_hfi_online (STB_GLOBAL)
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
