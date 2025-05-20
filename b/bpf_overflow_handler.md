# Function: <code>bpf_overflow_handler</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81199d90)
Location: kernel/events/core.c:7786
Inline: True
```
**Symbols:**

```
ffffffff81199d90-ffffffff81199e1f: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119fc40)
Location: kernel/events/core.c:8013
Inline: False
```
**Symbols:**

```
ffffffff8119fc40-ffffffff8119fcd2: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3620)
Location: kernel/events/core.c:8003
Inline: False
```
**Symbols:**

```
ffffffff811b3620-ffffffff811b36c2: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d4700)
Location: kernel/events/core.c:8503
Inline: True
```
**Symbols:**

```
ffffffff811d4700-ffffffff811d47a2: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e50c0)
Location: kernel/events/core.c:8543
Inline: True
```
**Symbols:**

```
ffffffff811e50c0-ffffffff811e5162: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fb490)
Location: kernel/events/core.c:8847
Inline: False
```
**Symbols:**

```
ffffffff811fb490-ffffffff811fb5a4: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208560)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
ffffffff81208560-ffffffff81208674: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812310e0)
Location: kernel/events/core.c:9513
Inline: False
```
**Symbols:**

```
ffffffff812310e0-ffffffff812311ee: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123acf0)
Location: kernel/events/core.c:9779
Inline: False
```
**Symbols:**

```
ffffffff8123acf0-ffffffff8123ae03: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f4c0)
Location: kernel/events/core.c:9909
Inline: False
```
**Symbols:**

```
ffffffff8123f4c0-ffffffff8123f5cc: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81279c30)
Location: kernel/events/core.c:10031
Inline: False
```
**Symbols:**

```
ffffffff81279c30-ffffffff81279d39: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812ccfc0)
Location: kernel/events/core.c:9966
Inline: False
```
**Symbols:**

```
ffffffff812ccfc0-ffffffff812cd0de: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81347940)
Location: kernel/events/core.c:10319
Inline: False
```
**Symbols:**

```
ffffffff81347940-ffffffff81347a8a: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81379210)
Location: kernel/events/core.c:10365
Inline: False
```
**Symbols:**

```
ffffffff81379210-ffffffff81379334: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a2520)
Location: kernel/events/core.c:10435
Inline: False
```
**Symbols:**

```
ffffffff813a2520-ffffffff813a2644: bpf_overflow_handler (STB_LOCAL)
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
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102970c0)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
ffff8000102970c0-ffff800010297200: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c05f4)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
c04c05f4-c04c077c: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033e020)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
c00000000033e020-c00000000033e1c8: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c37ee)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
ffffffe0001c37ee-ffffffe0001c38fe: bpf_overflow_handler (STB_LOCAL)
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
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200b80)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
ffffffff81200b80-ffffffff81200c94: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f38d0)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
ffffffff811f38d0-ffffffff811f39e4: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe950)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
ffffffff811fe950-ffffffff811fea64: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_overflow_handler(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d9c0)
Location: kernel/events/core.c:8963
Inline: False
```
**Symbols:**

```
ffffffff8120d9c0-ffffffff8120daf8: bpf_overflow_handler (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
