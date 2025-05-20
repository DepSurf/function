# Function: <code>perf_aux_output_flag</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811ae110)
Location: kernel/events/ring_buffer.c:300
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff811ae110-ffffffff811ae129: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c1c90)
Location: kernel/events/ring_buffer.c:300
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff811c1c90-ffffffff811c1ca8: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e2040)
Location: kernel/events/ring_buffer.c:301
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff811e2040-ffffffff811e2058: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f24b0)
Location: kernel/events/ring_buffer.c:301
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff811f24b0-ffffffff811f24c8: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120a1b0)
Location: kernel/events/ring_buffer.c:332
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8120a1b0-ffffffff8120a1c9: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81217490)
Location: kernel/events/ring_buffer.c:332
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff81217490-ffffffff812174a9: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81242e60)
Location: kernel/events/ring_buffer.c:332
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff81242e60-ffffffff81242e79: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124d540)
Location: kernel/events/ring_buffer.c:334
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8124d540-ffffffff8124d559: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81251e80)
Location: kernel/events/ring_buffer.c:334
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_start
```
**Symbols:**

```
ffffffff81251e80-ffffffff81251e99: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8128d700)
Location: kernel/events/ring_buffer.c:334
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_start
```
**Symbols:**

```
ffffffff8128d700-ffffffff8128d719: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e2490)
Location: kernel/events/ring_buffer.c:334
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_start
```
**Symbols:**

```
ffffffff812e2490-ffffffff812e24b9: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134aa40)
Location: kernel/events/ring_buffer.c:337
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_start
```
**Symbols:**

```
ffffffff8134aa40-ffffffff8134aa69: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137ba80)
Location: kernel/events/ring_buffer.c:337
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config_start
```
**Symbols:**

```
ffffffff8137ba80-ffffffff8137baa9: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a4cc0)
Location: kernel/events/ring_buffer.c:338
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
```
**Symbols:**

```
ffffffff813a4cc0-ffffffff813a4ce9: perf_aux_output_flag (STB_GLOBAL)
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
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a1d38)
Location: kernel/events/ring_buffer.c:332
Inline: False
```
**Symbols:**

```
ffff8000102a1d38-ffff8000102a1d80: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c04d1a04)
Location: kernel/events/ring_buffer.c:332
Inline: False
```
**Symbols:**

```
c04d1a04-c04d1a78: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c000000000353b80)
Location: kernel/events/ring_buffer.c:332
Inline: False
```
**Symbols:**

```
c000000000353b80-c000000000353ba8: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d09cc)
Location: kernel/events/ring_buffer.c:332
Inline: False
```
**Symbols:**

```
ffffffe0001d09cc-ffffffe0001d0a10: perf_aux_output_flag (STB_GLOBAL)
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
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120fae0)
Location: kernel/events/ring_buffer.c:332
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8120fae0-ffffffff8120faf9: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81202870)
Location: kernel/events/ring_buffer.c:332
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff81202870-ffffffff81202889: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120d880)
Location: kernel/events/ring_buffer.c:332
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8120d880-ffffffff8120d899: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_aux_output_flag(struct perf_output_handle *handle, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121c720)
Location: kernel/events/ring_buffer.c:332
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:intel_pt_handle_vmx
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8121c720-ffffffff8121c739: perf_aux_output_flag (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
