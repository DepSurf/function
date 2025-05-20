# Function: <code>bpf_perf_event_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 r1, u64 index, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81166f70)
Location: kernel/trace/bpf_trace.c:189
Inline: False
```
**Symbols:**

```
ffffffff81166f70-ffffffff81166fc0: bpf_perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 r1, u64 flags, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81174170)
Location: kernel/trace/bpf_trace.c:234
Inline: False
```
**Symbols:**

```
ffffffff81174170-ffffffff811741f8: bpf_perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117f9c0)
Location: kernel/trace/bpf_trace.c:231
Inline: False
```
**Symbols:**

```
ffffffff8117f9c0-ffffffff8117fa48: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182860)
Location: kernel/trace/bpf_trace.c:269
Inline: False
```
**Symbols:**

```
ffffffff81182860-ffffffff811828fd: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81190180)
Location: kernel/trace/bpf_trace.c:296
Inline: False
```
**Symbols:**

```
ffffffff81190180-ffffffff81190226: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a50a0)
Location: kernel/trace/bpf_trace.c:319
Inline: False
```
**Symbols:**

```
ffffffff811a50a0-ffffffff811a5146: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b31a0)
Location: kernel/trace/bpf_trace.c:355
Inline: False
```
**Symbols:**

```
ffffffff811b31a0-ffffffff811b3246: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1ef0)
Location: kernel/trace/bpf_trace.c:366
Inline: False
```
**Symbols:**

```
ffffffff811c1ef0-ffffffff811c1f9b: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cd660)
Location: kernel/trace/bpf_trace.c:369
Inline: False
```
**Symbols:**

```
ffffffff811cd660-ffffffff811cd70b: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e92b0)
Location: kernel/trace/bpf_trace.c:758
Inline: False
```
**Symbols:**

```
ffffffff811e92b0-ffffffff811e9358: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6690)
Location: kernel/trace/bpf_trace.c:841
Inline: False
```
**Symbols:**

```
ffffffff811e6690-ffffffff811e6738: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7930)
Location: kernel/trace/bpf_trace.c:518
Inline: False
```
**Symbols:**

```
ffffffff811e7930-ffffffff811e79d6: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812185b0)
Location: kernel/trace/bpf_trace.c:518
Inline: False
```
**Symbols:**

```
ffffffff812185b0-ffffffff81218656: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812568b0)
Location: kernel/trace/bpf_trace.c:570
Inline: False
```
**Symbols:**

```
ffffffff812568b0-ffffffff81256958: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a5cb0)
Location: kernel/trace/bpf_trace.c:573
Inline: False
```
**Symbols:**

```
ffffffff812a5cb0-ffffffff812a5d58: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c8180)
Location: kernel/trace/bpf_trace.c:571
Inline: False
```
**Symbols:**

```
ffffffff812c8180-ffffffff812c8228: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e4c10)
Location: kernel/trace/bpf_trace.c:571
Inline: False
```
**Symbols:**

```
ffffffff812e4c10-ffffffff812e4cb8: bpf_perf_event_read (STB_GLOBAL)
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024d378)
Location: kernel/trace/bpf_trace.c:369
Inline: False
```
**Symbols:**

```
ffff80001024d378-ffff80001024d43c: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047ffb8)
Location: kernel/trace/bpf_trace.c:369
Inline: False
```
**Symbols:**

```
c047ffb8-c04800b8: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e8e90)
Location: kernel/trace/bpf_trace.c:369
Inline: False
```
**Symbols:**

```
c0000000002e8e90-c0000000002e8f90: bpf_perf_event_read (STB_GLOBAL)
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5c80)
Location: kernel/trace/bpf_trace.c:369
Inline: False
```
**Symbols:**

```
ffffffff811c5c80-ffffffff811c5d2b: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8a60)
Location: kernel/trace/bpf_trace.c:369
Inline: False
```
**Symbols:**

```
ffffffff811b8a60-ffffffff811b8b0b: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3a50)
Location: kernel/trace/bpf_trace.c:369
Inline: False
```
**Symbols:**

```
ffffffff811c3a50-ffffffff811c3afb: bpf_perf_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d1330)
Location: kernel/trace/bpf_trace.c:369
Inline: False
```
**Symbols:**

```
ffffffff811d1330-ffffffff811d13db: bpf_perf_event_read (STB_GLOBAL)
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
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
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
