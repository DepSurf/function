# Function: <code>setup_pebs_time</code>

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
void setup_pebs_time(struct perf_event *event, struct perf_sample_data *data, u64 tsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81018140)
Location: arch/x86/events/intel/ds.c:1524
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff81018140-ffffffff810181b5: setup_pebs_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void setup_pebs_time(struct perf_event *event, struct perf_sample_data *data, u64 tsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017a20)
Location: arch/x86/events/intel/ds.c:1581
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff81017a20-ffffffff81017a95: setup_pebs_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void setup_pebs_time(struct perf_event *event, struct perf_sample_data *data, u64 tsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101d560)
Location: arch/x86/events/intel/ds.c:1586
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
**Symbols:**

```
ffffffff8101d560-ffffffff8101d5d5: setup_pebs_time (STB_LOCAL)
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
