# Function: <code>perf_pmu_snapshot_aux</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int perf_pmu_snapshot_aux(struct perf_buffer *rb, struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124095c)
Location: kernel/events/core.c:6495
Inline: True
```
**Symbols:**

```
ffffffff81240f30-ffffffff81240f90: perf_pmu_snapshot_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int perf_pmu_snapshot_aux(struct perf_buffer *rb, struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124af0c)
Location: kernel/events/core.c:6573
Inline: True
```
**Symbols:**

```
ffffffff8124b4c0-ffffffff8124b520: perf_pmu_snapshot_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int perf_pmu_snapshot_aux(struct perf_buffer *rb, struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124f540)
Location: kernel/events/core.c:6684
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff8124f540-ffffffff8124f5ae: perf_pmu_snapshot_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128a8c9)
Location: kernel/events/core.c:6808
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int perf_pmu_snapshot_aux(struct perf_buffer *rb, struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cc4c0)
Location: kernel/events/core.c:6713
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff812cc4c0-ffffffff812cc534: perf_pmu_snapshot_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int perf_pmu_snapshot_aux(struct perf_buffer *rb, struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813340c0)
Location: kernel/events/core.c:6971
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff813340c0-ffffffff81334146: perf_pmu_snapshot_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int perf_pmu_snapshot_aux(struct perf_buffer *rb, struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81364e30)
Location: kernel/events/core.c:6971
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81364e30-ffffffff81364eb6: perf_pmu_snapshot_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int perf_pmu_snapshot_aux(struct perf_buffer *rb, struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138de00)
Location: kernel/events/core.c:7044
Inline: False
Direct callers:
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff8138de00-ffffffff8138de86: perf_pmu_snapshot_aux (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
