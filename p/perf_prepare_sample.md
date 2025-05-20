# Function: <code>perf_prepare_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811834a0)
Location: kernel/events/core.c:5493
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
```
**Symbols:**

```
ffffffff811834a0-ffffffff811837e7: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811954e0)
Location: kernel/events/core.c:5820
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811954e0-ffffffff81195854: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a4f40)
Location: kernel/events/core.c:5918
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811a4f40-ffffffff811a529b: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ac580)
Location: kernel/events/core.c:6014
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811ac580-ffffffff811ac89d: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bff30)
Location: kernel/events/core.c:5999
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811bff30-ffffffff811c03e3: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e0300)
Location: kernel/events/core.c:6373
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811e0300-ffffffff811e07d1: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f0750)
Location: kernel/events/core.c:6382
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff811f0750-ffffffff811f0c3c: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207f10)
Location: kernel/events/core.c:6460
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81207f10-ffffffff81208406: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81215280)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81215280-ffffffff81215776: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812417b0)
Location: kernel/events/core.c:6979
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff812417b0-ffffffff81241be6: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124be90)
Location: kernel/events/core.c:7150
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8124be90-ffffffff8124c30c: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124ffb0)
Location: kernel/events/core.c:7261
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8124ffb0-ffffffff81250543: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128ad10)
Location: kernel/events/core.c:7385
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8128ad10-ffffffff8128b295: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812df770)
Location: kernel/events/core.c:7290
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff812df770-ffffffff812dfc77: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81347aa0)
Location: kernel/events/core.c:7557
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81347aa0-ffffffff8134808c: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81378a40)
Location: kernel/events/core.c:7575
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff81378a40-ffffffff81378fdb: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a1d40)
Location: kernel/events/core.c:7656
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff813a1d40-ffffffff813a22ea: perf_prepare_sample (STB_GLOBAL)
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
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029f2d8)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffff80001029f2d8-ffff80001029f778: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cf0f0)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
c04cf0f0-c04cf62c: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000350580)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
c000000000350580-c000000000350bdc: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cebea)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffe0001cebea-ffffffe0001cf078: perf_prepare_sample (STB_GLOBAL)
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
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d8d0)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8120d8d0-ffffffff8120ddc6: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812006a0)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff812006a0-ffffffff81200b96: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b670)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8120b670-ffffffff8120bb66: perf_prepare_sample (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_prepare_sample(struct perf_event_header *header, struct perf_sample_data *data, struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121a480)
Location: kernel/events/core.c:6576
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - kernel/events/core.c:perf_event_output
  - kernel/events/core.c:perf_event_output_backward
  - kernel/events/core.c:perf_event_output_forward
```
**Symbols:**

```
ffffffff8121a480-ffffffff8121a976: perf_prepare_sample (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct perf_event_header *header</code>
</li>
<li>
<b>Param reordered. </b>
<code>header, data, event, regs</code> ➡️ <code>data, event, regs</code>
</li>
</ul>
</details>
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
