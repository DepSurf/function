# Function: <code>uncore_die_to_segment</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uncore_die_to_segment(int die);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ae40)
Location: arch/x86/events/intel/uncore.c:56
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_iio_set_mapping
```
**Symbols:**

```
ffffffff8101ae40-ffffffff8101aed7: uncore_die_to_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uncore_die_to_segment(int die);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101d740)
Location: arch/x86/events/intel/uncore.c:56
Inline: False
```
**Symbols:**

```
ffffffff8101d740-ffffffff8101d7d7: uncore_die_to_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uncore_die_to_segment(int die);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81020110)
Location: arch/x86/events/intel/uncore.c:56
Inline: False
```
**Symbols:**

```
ffffffff81020110-ffffffff810201c0: uncore_die_to_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uncore_die_to_segment(int die);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810249b0)
Location: arch/x86/events/intel/uncore.c:56
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
```
**Symbols:**

```
ffffffff810249b0-ffffffff81024a60: uncore_die_to_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uncore_die_to_segment(int die);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81024710)
Location: arch/x86/events/intel/uncore.c:56
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
```
**Symbols:**

```
ffffffff81024710-ffffffff810247c4: uncore_die_to_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uncore_die_to_segment(int die);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8102a840)
Location: arch/x86/events/intel/uncore.c:56
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
```
**Symbols:**

```
ffffffff8102a840-ffffffff8102a8f4: uncore_die_to_segment (STB_GLOBAL)
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
