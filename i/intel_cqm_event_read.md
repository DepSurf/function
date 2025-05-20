# Function: <code>intel_cqm_event_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_cqm_event_read(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100e050)
Location: arch/x86/events/intel/cqm.c:1038
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_stop
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_stop
```
**Symbols:**

```
ffffffff8100e050-ffffffff8100e0c3: intel_cqm_event_read.part.1 (STB_LOCAL)
ffffffff8100e0d0-ffffffff8100e0ea: intel_cqm_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_cqm_event_read(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100dc50)
Location: arch/x86/events/intel/cqm.c:1045
Inline: True
```
**Symbols:**

```
ffffffff8100dc50-ffffffff8100dcc3: intel_cqm_event_read.part.2 (STB_LOCAL)
ffffffff8100dcd0-ffffffff8100dcea: intel_cqm_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_cqm_event_read(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100dd10)
Location: arch/x86/events/intel/cqm.c:1026
Inline: True
```
**Symbols:**

```
ffffffff8100dd10-ffffffff8100dd83: intel_cqm_event_read.part.4 (STB_LOCAL)
ffffffff8100dd90-ffffffff8100ddaa: intel_cqm_event_read (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
