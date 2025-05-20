# Function: <code>perf_output_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81182e40)
Location: kernel/events/core.c:5333
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
```
**Symbols:**

```
ffffffff81182e40-ffffffff81183499: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81194d80)
Location: kernel/events/core.c:5650
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81194d80-ffffffff811954d2: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a47e0)
Location: kernel/events/core.c:5748
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811a47e0-ffffffff811a4f32: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811abe20)
Location: kernel/events/core.c:5844
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811abe20-ffffffff811ac571: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bf7a0)
Location: kernel/events/core.c:5794
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811bf7a0-ffffffff811bff27: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dfa60)
Location: kernel/events/core.c:6156
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811dfa60-ffffffff811e0278: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811efeb0)
Location: kernel/events/core.c:6165
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811efeb0-ffffffff811f06c8: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812076c0)
Location: kernel/events/core.c:6243
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff812076c0-ffffffff81207e7e: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81214a30)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81214a30-ffffffff812151ee: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240fd0)
Location: kernel/events/core.c:6747
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81240fd0-ffffffff81241716: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124b560)
Location: kernel/events/core.c:6825
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8124b560-ffffffff8124bdfd: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124f5f0)
Location: kernel/events/core.c:6936
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8124f5f0-ffffffff8124ff15: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128a310)
Location: kernel/events/core.c:7060
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8128a310-ffffffff8128ac78: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812ded90)
Location: kernel/events/core.c:6965
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff812ded90-ffffffff812df698: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81346fd0)
Location: kernel/events/core.c:7232
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81346fd0-ffffffff81347844: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813780e0)
Location: kernel/events/core.c:7241
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff813780e0-ffffffff81378942: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a13c0)
Location: kernel/events/core.c:7314
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff813a13c0-ffffffff813a1c44: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029ed00)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffff80001029ed00-ffff80001029f248: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04ce6e4)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
c04ce6e4-c04cf038: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034fcf0)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - arch/powerpc/perf/imc-pmu.c:dump_trace_imc_data
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
c00000000034fcf0-c0000000003504c8: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001ce4b2)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffe0001ce4b2-ffffffe0001ceb78: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d080)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8120d080-ffffffff8120d83e: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffe50)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811ffe50-ffffffff8120060e: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ae20)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8120ae20-ffffffff8120b5de: perf_output_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_output_sample(struct perf_output_handle *handle, struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81219c30)
Location: kernel/events/core.c:6359
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81219c30-ffffffff8121a3ee: perf_output_sample (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
