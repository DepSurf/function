# Function: <code>tracepoint_probe_register_prio_may_exist</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracepoint_probe_register_prio_may_exist(struct tracepoint *tp, void *probe, void *data, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a9df0)
Location: kernel/tracepoint.c:472
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff811a9df0-ffffffff811a9e7b: tracepoint_probe_register_prio_may_exist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tracepoint_probe_register_prio_may_exist(struct tracepoint *tp, void *probe, void *data, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811d3960)
Location: kernel/tracepoint.c:472
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff811d3960-ffffffff811d39eb: tracepoint_probe_register_prio_may_exist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tracepoint_probe_register_prio_may_exist(struct tracepoint *tp, void *probe, void *data, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81208410)
Location: kernel/tracepoint.c:472
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff81208410-ffffffff812084ba: tracepoint_probe_register_prio_may_exist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tracepoint_probe_register_prio_may_exist(struct tracepoint *tp, void *probe, void *data, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81250500)
Location: kernel/tracepoint.c:472
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff81250500-ffffffff812505aa: tracepoint_probe_register_prio_may_exist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tracepoint_probe_register_prio_may_exist(struct tracepoint *tp, void *probe, void *data, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff812678b0)
Location: kernel/tracepoint.c:472
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff812678b0-ffffffff8126795a: tracepoint_probe_register_prio_may_exist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tracepoint_probe_register_prio_may_exist(struct tracepoint *tp, void *probe, void *data, int prio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81281be0)
Location: kernel/tracepoint.c:472
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff81281be0-ffffffff81281c8a: tracepoint_probe_register_prio_may_exist (STB_GLOBAL)
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
