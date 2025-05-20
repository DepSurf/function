# Function: <code>bpf_probe_read_str</code>

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
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182810)
Location: kernel/trace/bpf_trace.c:432
Inline: False
```
**Symbols:**

```
ffffffff81182810-ffffffff81182855: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8118fe40)
Location: kernel/trace/bpf_trace.c:476
Inline: False
```
**Symbols:**

```
ffffffff8118fe40-ffffffff8118fe85: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4d50)
Location: kernel/trace/bpf_trace.c:497
Inline: False
```
**Symbols:**

```
ffffffff811a4d50-ffffffff811a4d8d: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2e20)
Location: kernel/trace/bpf_trace.c:533
Inline: False
```
**Symbols:**

```
ffffffff811b2e20-ffffffff811b2e5d: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1b50)
Location: kernel/trace/bpf_trace.c:567
Inline: False
```
**Symbols:**

```
ffffffff811c1b50-ffffffff811c1b95: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cd300)
Location: kernel/trace/bpf_trace.c:586
Inline: False
```
**Symbols:**

```
ffffffff811cd300-ffffffff811cd360: bpf_probe_read_str (STB_GLOBAL)
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
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024c7b0)
Location: kernel/trace/bpf_trace.c:586
Inline: False
```
**Symbols:**

```
ffff80001024c7b0-ffff80001024c830: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047fb70)
Location: kernel/trace/bpf_trace.c:586
Inline: False
```
**Symbols:**

```
c047fb70-c047fbd0: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e88f0)
Location: kernel/trace/bpf_trace.c:586
Inline: False
```
**Symbols:**

```
c0000000002e88f0-c0000000002e89b8: bpf_probe_read_str (STB_GLOBAL)
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
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5920)
Location: kernel/trace/bpf_trace.c:586
Inline: False
```
**Symbols:**

```
ffffffff811c5920-ffffffff811c5980: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8700)
Location: kernel/trace/bpf_trace.c:586
Inline: False
```
**Symbols:**

```
ffffffff811b8700-ffffffff811b8760: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c36f0)
Location: kernel/trace/bpf_trace.c:586
Inline: False
```
**Symbols:**

```
ffffffff811c36f0-ffffffff811c3750: bpf_probe_read_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_probe_read_str(u64 dst, u64 size, u64 unsafe_ptr, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d0fd0)
Location: kernel/trace/bpf_trace.c:586
Inline: False
```
**Symbols:**

```
ffffffff811d0fd0-ffffffff811d1030: bpf_probe_read_str (STB_GLOBAL)
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
