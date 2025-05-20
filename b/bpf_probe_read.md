# Function: <code>bpf_probe_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81166fc0)
Location: kernel/trace/bpf_trace.c:64
Inline: False
```
**Symbols:**

```
ffffffff81166fc0-ffffffff81166fd4: bpf_probe_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81174200)
Location: kernel/trace/bpf_trace.c:62
Inline: False
```
**Symbols:**

```
ffffffff81174200-ffffffff81174245: bpf_probe_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117f6d0)
Location: kernel/trace/bpf_trace.c:64
Inline: False
```
**Symbols:**

```
ffffffff8117f6d0-ffffffff8117f715: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811823d0)
Location: kernel/trace/bpf_trace.c:64
Inline: False
```
**Symbols:**

```
ffffffff811823d0-ffffffff81182433: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8118fd90)
Location: kernel/trace/bpf_trace.c:79
Inline: False
```
**Symbols:**

```
ffffffff8118fd90-ffffffff8118fdd5: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4cb0)
Location: kernel/trace/bpf_trace.c:102
Inline: False
```
**Symbols:**

```
ffffffff811a4cb0-ffffffff811a4ced: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2d80)
Location: kernel/trace/bpf_trace.c:136
Inline: False
```
**Symbols:**

```
ffffffff811b2d80-ffffffff811b2dbd: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1a90)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
ffffffff811c1a90-ffffffff811c1ad5: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cd240)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
ffffffff811cd240-ffffffff811cd2a0: bpf_probe_read (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024c6e0)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
ffff80001024c6e0-ffff80001024c760: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047fa98)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
c047fa98-c047faf8: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e87b0)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
c0000000002e87b0-c0000000002e8878: bpf_probe_read (STB_GLOBAL)
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
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5860)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
ffffffff811c5860-ffffffff811c58c0: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8640)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
ffffffff811b8640-ffffffff811b86a0: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3630)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
ffffffff811c3630-ffffffff811c3690: bpf_probe_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_probe_read(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d0f10)
Location: kernel/trace/bpf_trace.c:141
Inline: False
```
**Symbols:**

```
ffffffff811d0f10-ffffffff811d0f70: bpf_probe_read (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 dst</code>
</li>
<li>
<b>Param added. </b>
<code>u64 size</code>
</li>
<li>
<b>Param added. </b>
<code>u64 unsafe_ptr</code>
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
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
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
