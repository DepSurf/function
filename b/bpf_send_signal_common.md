# Function: <code>bpf_send_signal_common</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_send_signal_common(u32 sig, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9740)
Location: kernel/trace/bpf_trace.c:992
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_thread
  - kernel/trace/bpf_trace.c:bpf_send_signal
```
**Symbols:**

```
ffffffff811e9740-ffffffff811e980b: bpf_send_signal_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_send_signal_common(u32 sig, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6b10)
Location: kernel/trace/bpf_trace.c:1089
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_thread
  - kernel/trace/bpf_trace.c:bpf_send_signal
```
**Symbols:**

```
ffffffff811e6b10-ffffffff811e6bd1: bpf_send_signal_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_send_signal_common(u32 sig, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7db0)
Location: kernel/trace/bpf_trace.c:766
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_thread
  - kernel/trace/bpf_trace.c:bpf_send_signal
```
**Symbols:**

```
ffffffff811e7db0-ffffffff811e7e71: bpf_send_signal_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_send_signal_common(u32 sig, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81218a30)
Location: kernel/trace/bpf_trace.c:781
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_thread
  - kernel/trace/bpf_trace.c:bpf_send_signal
```
**Symbols:**

```
ffffffff81218a30-ffffffff81218af1: bpf_send_signal_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_send_signal_common(u32 sig, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81256d90)
Location: kernel/trace/bpf_trace.c:833
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_thread
  - kernel/trace/bpf_trace.c:bpf_send_signal
```
**Symbols:**

```
ffffffff81256d90-ffffffff81256e70: bpf_send_signal_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_send_signal_common(u32 sig, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a6bf0)
Location: kernel/trace/bpf_trace.c:839
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_thread
  - kernel/trace/bpf_trace.c:bpf_send_signal
```
**Symbols:**

```
ffffffff812a6bf0-ffffffff812a6d34: bpf_send_signal_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_send_signal_common(u32 sig, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c8cb0)
Location: kernel/trace/bpf_trace.c:842
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_thread
  - kernel/trace/bpf_trace.c:bpf_send_signal
```
**Symbols:**

```
ffffffff812c8cb0-ffffffff812c8df4: bpf_send_signal_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_send_signal_common(u32 sig, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e5c80)
Location: kernel/trace/bpf_trace.c:842
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_thread
  - kernel/trace/bpf_trace.c:bpf_send_signal
```
**Symbols:**

```
ffffffff812e5c80-ffffffff812e5dc4: bpf_send_signal_common (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
