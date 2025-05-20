# Function: <code>bpf_probe_write_user</code>

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
u64 bpf_probe_write_user(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811743a0)
Location: kernel/trace/bpf_trace.c:84
Inline: False
```
**Symbols:**

```
ffffffff811743a0-ffffffff811743f4: bpf_probe_write_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117f720)
Location: kernel/trace/bpf_trace.c:84
Inline: False
```
**Symbols:**

```
ffffffff8117f720-ffffffff8117f773: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182440)
Location: kernel/trace/bpf_trace.c:89
Inline: False
```
**Symbols:**

```
ffffffff81182440-ffffffff811824b9: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8118fde0)
Location: kernel/trace/bpf_trace.c:99
Inline: False
```
**Symbols:**

```
ffffffff8118fde0-ffffffff8118fe32: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4cf0)
Location: kernel/trace/bpf_trace.c:122
Inline: False
```
**Symbols:**

```
ffffffff811a4cf0-ffffffff811a4d42: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2dc0)
Location: kernel/trace/bpf_trace.c:156
Inline: False
```
**Symbols:**

```
ffffffff811b2dc0-ffffffff811b2e18: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1ae0)
Location: kernel/trace/bpf_trace.c:161
Inline: False
```
**Symbols:**

```
ffffffff811c1ae0-ffffffff811c1b41: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cd2a0)
Location: kernel/trace/bpf_trace.c:166
Inline: False
```
**Symbols:**

```
ffffffff811cd2a0-ffffffff811cd2fb: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8d50)
Location: kernel/trace/bpf_trace.c:305
Inline: False
```
**Symbols:**

```
ffffffff811e8d50-ffffffff811e8dbf: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6130)
Location: kernel/trace/bpf_trace.c:328
Inline: False
```
**Symbols:**

```
ffffffff811e6130-ffffffff811e6195: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e77f0)
Location: kernel/trace/bpf_trace.c:316
Inline: False
```
**Symbols:**

```
ffffffff811e77f0-ffffffff811e7855: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81218470)
Location: kernel/trace/bpf_trace.c:316
Inline: False
```
**Symbols:**

```
ffffffff81218470-ffffffff812184d5: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81256730)
Location: kernel/trace/bpf_trace.c:324
Inline: False
```
**Symbols:**

```
ffffffff81256730-ffffffff812567b3: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a5b00)
Location: kernel/trace/bpf_trace.c:327
Inline: False
```
**Symbols:**

```
ffffffff812a5b00-ffffffff812a5b83: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c7fb0)
Location: kernel/trace/bpf_trace.c:327
Inline: False
```
**Symbols:**

```
ffffffff812c7fb0-ffffffff812c8033: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e4a40)
Location: kernel/trace/bpf_trace.c:327
Inline: False
```
**Symbols:**

```
ffffffff812e4a40-ffffffff812e4ac3: bpf_probe_write_user (STB_GLOBAL)
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024c760)
Location: kernel/trace/bpf_trace.c:166
Inline: False
```
**Symbols:**

```
ffff80001024c760-ffff80001024c7b0: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047faf8)
Location: kernel/trace/bpf_trace.c:166
Inline: False
```
**Symbols:**

```
c047faf8-c047fb70: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e8880)
Location: kernel/trace/bpf_trace.c:166
Inline: False
```
**Symbols:**

```
c0000000002e8880-c0000000002e88ec: bpf_probe_write_user (STB_GLOBAL)
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
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c58c0)
Location: kernel/trace/bpf_trace.c:166
Inline: False
```
**Symbols:**

```
ffffffff811c58c0-ffffffff811c591b: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b86a0)
Location: kernel/trace/bpf_trace.c:166
Inline: False
```
**Symbols:**

```
ffffffff811b86a0-ffffffff811b86fb: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3690)
Location: kernel/trace/bpf_trace.c:166
Inline: False
```
**Symbols:**

```
ffffffff811c3690-ffffffff811c36eb: bpf_probe_write_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_probe_write_user(u64 unsafe_ptr, u64 src, u64 size, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d0f70)
Location: kernel/trace/bpf_trace.c:166
Inline: False
```
**Symbols:**

```
ffffffff811d0f70-ffffffff811d0fcb: bpf_probe_write_user (STB_GLOBAL)
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
<code>u64 unsafe_ptr</code>
</li>
<li>
<b>Param added. </b>
<code>u64 src</code>
</li>
<li>
<b>Param added. </b>
<code>u64 size</code>
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
