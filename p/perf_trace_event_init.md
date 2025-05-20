# Function: <code>perf_trace_event_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8116267e)
Location: kernel/trace/trace_event_perf.c:185
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8116ce4c)
Location: kernel/trace/trace_event_perf.c:188
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8117810c)
Location: kernel/trace/trace_event_perf.c:188
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8117ae1c)
Location: kernel/trace/trace_event_perf.c:188
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8118867c)
Location: kernel/trace/trace_event_perf.c:188
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811977c0)
Location: kernel/trace/trace_event_perf.c:189
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811977c0-ffffffff81197a26: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811a5930)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811a5930-ffffffff811a5b96: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811b3840)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811b3840-ffffffff811b3aa5: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811bee30)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811bee30-ffffffff811bf095: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811d8940)
Location: kernel/trace/trace_event_perf.c:195
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811d8940-ffffffff811d89a6: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811d5a60)
Location: kernel/trace/trace_event_perf.c:195
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811d5a60-ffffffff811d5ac6: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811d6e50)
Location: kernel/trace/trace_event_perf.c:195
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811d6e50-ffffffff811d7104: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff81203d50)
Location: kernel/trace/trace_event_perf.c:195
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff81203d50-ffffffff81204093: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8123f120)
Location: kernel/trace/trace_event_perf.c:193
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff8123f120-ffffffff8123f487: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8128cdb0)
Location: kernel/trace/trace_event_perf.c:193
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff8128cdb0-ffffffff8128cf32: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff812a9d30)
Location: kernel/trace/trace_event_perf.c:193
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff812a9d30-ffffffff812a9eb2: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff812c5a40)
Location: kernel/trace/trace_event_perf.c:193
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff812c5a40-ffffffff812c5bc2: perf_trace_event_init (STB_LOCAL)
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
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffff80001023e2a0)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffff80001023e2a0-ffff80001023e514: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (c0479ac8)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
c0479ac8-c0479d48: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (c0000000002ce050)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
c0000000002ce050-c0000000002ce3d0: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffe000193de2)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811b7450)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811b7450-ffffffff811b76b5: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811aa230)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811aa230-ffffffff811aa495: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811b5220)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811b5220-ffffffff811b5485: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int perf_trace_event_init(struct trace_event_call *tp_event, struct perf_event *p_event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811c32c0)
Location: kernel/trace/trace_event_perf.c:190
Inline: True
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_uprobe_init
  - kernel/trace/trace_event_perf.c:perf_kprobe_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
```
**Symbols:**

```
ffffffff811c32c0-ffffffff811c3525: perf_trace_event_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
