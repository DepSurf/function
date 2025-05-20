# Function: <code>get_data_src</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f810)
Location: arch/x86/events/intel/ds.c:1281
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff8100f810-ffffffff8100f8ca: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fef0)
Location: arch/x86/events/intel/ds.c:1324
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff8100fef0-ffffffff8100ffaa: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011390)
Location: arch/x86/events/intel/ds.c:1325
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff81011390-ffffffff8101144e: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810109c0)
Location: arch/x86/events/intel/ds.c:1326
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff810109c0-ffffffff81010a7e: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810118e0)
Location: arch/x86/events/intel/ds.c:1423
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff810118e0-ffffffff81011a36: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810127b0)
Location: arch/x86/events/intel/ds.c:1432
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff810127b0-ffffffff8101290e: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 get_data_src(struct perf_event *event, u64 aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810143c0)
Location: arch/x86/events/intel/ds.c:1488
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff810143c0-ffffffff810145f2: get_data_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 get_data_src(struct perf_event *event, u64 aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81018590)
Location: arch/x86/events/intel/ds.c:1505
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff81018590-ffffffff810187c2: get_data_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 get_data_src(struct perf_event *event, u64 aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017e70)
Location: arch/x86/events/intel/ds.c:1562
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff81017e70-ffffffff810180a2: get_data_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 get_data_src(struct perf_event *event, u64 aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101d9e0)
Location: arch/x86/events/intel/ds.c:1567
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff8101d9e0-ffffffff8101dc27: get_data_src (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fef0)
Location: arch/x86/events/intel/ds.c:1324
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff8100fef0-ffffffff8100ffaa: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100ec90)
Location: arch/x86/events/intel/ds.c:1324
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff8100ec90-ffffffff8100ed4a: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100feb0)
Location: arch/x86/events/intel/ds.c:1324
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff8100feb0-ffffffff8100ff6a: get_data_src.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810100c0)
Location: arch/x86/events/intel/ds.c:1324
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff810100c0-ffffffff8101017a: get_data_src.isra.0 (STB_LOCAL)
```
</details>
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
