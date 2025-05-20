# Function: <code>perf_callchain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81186230)
Location: kernel/events/callchain.c:160
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81186230-ffffffff81186405: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81198760)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81198760-ffffffff811987e1: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811a8140)
Location: kernel/events/callchain.c:180
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff811a8140-ffffffff811a81c1: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811af900)
Location: kernel/events/callchain.c:182
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff811af900-ffffffff811af977: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff811c34a0)
Location: kernel/events/callchain.c:182
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff811c34a0-ffffffff811c3515: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e0280)
Location: kernel/events/core.c:6356
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff811e0280-ffffffff811e02fe: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f06d0)
Location: kernel/events/core.c:6365
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff811f06d0-ffffffff811f074e: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207e80)
Location: kernel/events/core.c:6443
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81207e80-ffffffff81207f07: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812151f0)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff812151f0-ffffffff81215277: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241720)
Location: kernel/events/core.c:6962
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81241720-ffffffff812417a7: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124be00)
Location: kernel/events/core.c:7133
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8124be00-ffffffff8124be87: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124ff20)
Location: kernel/events/core.c:7244
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8124ff20-ffffffff8124ffa7: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128ac80)
Location: kernel/events/core.c:7368
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8128ac80-ffffffff8128ad07: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812df6a0)
Location: kernel/events/core.c:7273
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff812df6a0-ffffffff812df769: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81347860)
Location: kernel/events/core.c:7540
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81347860-ffffffff81347929: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81378960)
Location: kernel/events/core.c:7553
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81378960-ffffffff81378a29: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a1c60)
Location: kernel/events/core.c:7634
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff813a1c60-ffffffff813a1d29: perf_callchain (STB_GLOBAL)
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
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029f248)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffff80001029f248-ffff80001029f2d4: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cf038)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
c04cf038-c04cf0f0: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003504d0)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
c0000000003504d0-c00000000035057c: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001ceb78)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffe0001ceb78-ffffffe0001cebea: perf_callchain (STB_GLOBAL)
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
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d840)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8120d840-ffffffff8120d8c7: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200610)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81200610-ffffffff81200697: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b5e0)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8120b5e0-ffffffff8120b667: perf_callchain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct perf_callchain_entry *perf_callchain(struct perf_event *event, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121a3f0)
Location: kernel/events/core.c:6559
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8121a3f0-ffffffff8121a477: perf_callchain (STB_GLOBAL)
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
