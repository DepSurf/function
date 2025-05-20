# Function: <code>bpf_perf_event_output_tp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 r1, u64 r2, u64 index, u64 r4, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81174150)
Location: kernel/trace/bpf_trace.c:450
Inline: False
```
**Symbols:**

```
ffffffff81174150-ffffffff8117415e: bpf_perf_event_output_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117fb90)
Location: kernel/trace/bpf_trace.c:475
Inline: False
```
**Symbols:**

```
ffffffff8117fb90-ffffffff8117fcc5: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182a30)
Location: kernel/trace/bpf_trace.c:543
Inline: False
```
**Symbols:**

```
ffffffff81182a30-ffffffff81182b58: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81190480)
Location: kernel/trace/bpf_trace.c:592
Inline: False
```
**Symbols:**

```
ffffffff81190480-ffffffff8119059f: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5390)
Location: kernel/trace/bpf_trace.c:626
Inline: False
```
**Symbols:**

```
ffffffff811a5390-ffffffff811a54af: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b3490)
Location: kernel/trace/bpf_trace.c:662
Inline: False
```
**Symbols:**

```
ffffffff811b3490-ffffffff811b35bf: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2220)
Location: kernel/trace/bpf_trace.c:767
Inline: False
```
**Symbols:**

```
ffffffff811c2220-ffffffff811c237f: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cd990)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
ffffffff811cd990-ffffffff811cdaef: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e95d0)
Location: kernel/trace/bpf_trace.c:1190
Inline: False
```
**Symbols:**

```
ffffffff811e95d0-ffffffff811e9732: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e69b0)
Location: kernel/trace/bpf_trace.c:1419
Inline: False
```
**Symbols:**

```
ffffffff811e69b0-ffffffff811e6b0b: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7c50)
Location: kernel/trace/bpf_trace.c:1113
Inline: False
```
**Symbols:**

```
ffffffff811e7c50-ffffffff811e7dae: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812188d0)
Location: kernel/trace/bpf_trace.c:1190
Inline: False
```
**Symbols:**

```
ffffffff812188d0-ffffffff81218a2e: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81256c20)
Location: kernel/trace/bpf_trace.c:1368
Inline: False
```
**Symbols:**

```
ffffffff81256c20-ffffffff81256d86: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a6040)
Location: kernel/trace/bpf_trace.c:1582
Inline: False
```
**Symbols:**

```
ffffffff812a6040-ffffffff812a6186: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812ca940)
Location: kernel/trace/bpf_trace.c:1591
Inline: False
```
**Symbols:**

```
ffffffff812ca940-ffffffff812cab3e: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e7be0)
Location: kernel/trace/bpf_trace.c:1696
Inline: False
```
**Symbols:**

```
ffffffff812e7be0-ffffffff812e7dde: bpf_perf_event_output_tp (STB_GLOBAL)
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
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024d8b0)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
ffff80001024d8b0-ffff80001024da30: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0480430)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
c0480430-c0480648: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e93a0)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
c0000000002e93a0-c0000000002e95d0: bpf_perf_event_output_tp (STB_GLOBAL)
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
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5fb0)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
ffffffff811c5fb0-ffffffff811c610f: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8d90)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
ffffffff811b8d90-ffffffff811b8eef: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3d80)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
ffffffff811c3d80-ffffffff811c3edf: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_perf_event_output_tp(u64 tp_buff, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d1660)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
ffffffff811d1660-ffffffff811d17bf: bpf_perf_event_output_tp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 tp_buff</code>
</li>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 flags</code>
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
<code>u64 index</code>
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
