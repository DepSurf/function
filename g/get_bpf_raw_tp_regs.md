# Function: <code>get_bpf_raw_tp_regs</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1160)
Location: kernel/trace/bpf_trace.c:927
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
ffffffff811c1160-ffffffff811c11a4: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cc910)
Location: kernel/trace/bpf_trace.c:951
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
ffffffff811cc910-ffffffff811cc954: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ea320)
Location: kernel/trace/bpf_trace.c:1391
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e82f6)
Location: kernel/trace/bpf_trace.c:1620
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e90e3)
Location: kernel/trace/bpf_trace.c:1314
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
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
In kernel/trace/bpf_trace.c (ffffffff81219b63)
Location: kernel/trace/bpf_trace.c:1391
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812582e3)
Location: kernel/trace/bpf_trace.c:1569
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a8073)
Location: kernel/trace/bpf_trace.c:1786
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812ca34e)
Location: kernel/trace/bpf_trace.c:1795
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e74ce)
Location: kernel/trace/bpf_trace.c:1900
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024da30)
Location: kernel/trace/bpf_trace.c:951
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
ffff80001024da30-ffff80001024daa8: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0480aa0)
Location: kernel/trace/bpf_trace.c:951
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
c0480aa0-c0480b58: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e9b00)
Location: kernel/trace/bpf_trace.c:951
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
c0000000002e9b00-c0000000002e9bec: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4f30)
Location: kernel/trace/bpf_trace.c:951
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
ffffffff811c4f30-ffffffff811c4f74: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b7d10)
Location: kernel/trace/bpf_trace.c:951
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
ffffffff811b7d10-ffffffff811b7d54: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2d00)
Location: kernel/trace/bpf_trace.c:951
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
ffffffff811c2d00-ffffffff811c2d44: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pt_regs *get_bpf_raw_tp_regs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d0da0)
Location: kernel/trace/bpf_trace.c:951
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
```
**Symbols:**

```
ffffffff811d0da0-ffffffff811d0de4: get_bpf_raw_tp_regs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
