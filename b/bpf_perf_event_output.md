# Function: <code>bpf_perf_event_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 r1, u64 r2, u64 index, u64 r4, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81166e80)
Location: kernel/trace/bpf_trace.c:223
Inline: False
```
**Symbols:**

```
ffffffff81166e80-ffffffff81166f70: bpf_perf_event_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 r1, u64 r2, u64 flags, u64 r4, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81174010)
Location: kernel/trace/bpf_trace.c:313
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
```
**Symbols:**

```
ffffffff81174010-ffffffff81174148: bpf_perf_event_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117fa50)
Location: kernel/trace/bpf_trace.c:309
Inline: False
```
**Symbols:**

```
ffffffff8117fa50-ffffffff8117fb88: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182900)
Location: kernel/trace/bpf_trace.c:343
Inline: False
```
**Symbols:**

```
ffffffff81182900-ffffffff81182a2b: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81190350)
Location: kernel/trace/bpf_trace.c:379
Inline: False
```
**Symbols:**

```
ffffffff81190350-ffffffff81190472: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5260)
Location: kernel/trace/bpf_trace.c:402
Inline: False
```
**Symbols:**

```
ffffffff811a5260-ffffffff811a5382: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b3360)
Location: kernel/trace/bpf_trace.c:438
Inline: False
```
**Symbols:**

```
ffffffff811b3360-ffffffff811b3490: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c20b0)
Location: kernel/trace/bpf_trace.c:456
Inline: False
```
**Symbols:**

```
ffffffff811c20b0-ffffffff811c2212: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cd820)
Location: kernel/trace/bpf_trace.c:459
Inline: False
```
**Symbols:**

```
ffffffff811cd820-ffffffff811cd982: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9470)
Location: kernel/trace/bpf_trace.c:848
Inline: False
```
**Symbols:**

```
ffffffff811e9470-ffffffff811e95cd: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6850)
Location: kernel/trace/bpf_trace.c:931
Inline: False
```
**Symbols:**

```
ffffffff811e6850-ffffffff811e69a6: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7af0)
Location: kernel/trace/bpf_trace.c:608
Inline: False
```
**Symbols:**

```
ffffffff811e7af0-ffffffff811e7c4b: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81218770)
Location: kernel/trace/bpf_trace.c:608
Inline: False
```
**Symbols:**

```
ffffffff81218770-ffffffff812188cb: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81256ab0)
Location: kernel/trace/bpf_trace.c:660
Inline: False
```
**Symbols:**

```
ffffffff81256ab0-ffffffff81256c13: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a5ee0)
Location: kernel/trace/bpf_trace.c:663
Inline: False
```
**Symbols:**

```
ffffffff812a5ee0-ffffffff812a6023: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812ca730)
Location: kernel/trace/bpf_trace.c:661
Inline: False
```
**Symbols:**

```
ffffffff812ca730-ffffffff812ca925: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e79d0)
Location: kernel/trace/bpf_trace.c:661
Inline: False
```
**Symbols:**

```
ffffffff812e79d0-ffffffff812e7bc5: bpf_perf_event_output (STB_GLOBAL)
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
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024d730)
Location: kernel/trace/bpf_trace.c:459
Inline: False
```
**Symbols:**

```
ffff80001024d730-ffff80001024d8b0: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0480218)
Location: kernel/trace/bpf_trace.c:459
Inline: False
```
**Symbols:**

```
c0480218-c0480430: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e9170)
Location: kernel/trace/bpf_trace.c:459
Inline: False
```
**Symbols:**

```
c0000000002e9170-c0000000002e93a0: bpf_perf_event_output (STB_GLOBAL)
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
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5e40)
Location: kernel/trace/bpf_trace.c:459
Inline: False
```
**Symbols:**

```
ffffffff811c5e40-ffffffff811c5fa2: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8c20)
Location: kernel/trace/bpf_trace.c:459
Inline: False
```
**Symbols:**

```
ffffffff811b8c20-ffffffff811b8d82: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3c10)
Location: kernel/trace/bpf_trace.c:459
Inline: False
```
**Symbols:**

```
ffffffff811c3c10-ffffffff811c3d72: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_perf_event_output(u64 regs, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d14f0)
Location: kernel/trace/bpf_trace.c:459
Inline: False
```
**Symbols:**

```
ffffffff811d14f0-ffffffff811d1652: bpf_perf_event_output (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 index</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 regs</code>
</li>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 data</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
</ul>
</details>
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
