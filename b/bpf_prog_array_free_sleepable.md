# Function: <code>bpf_prog_array_free_sleepable</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_prog_array_free_sleepable(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c3500)
Location: kernel/bpf/core.c:2266
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff812c3500-ffffffff812c3536: bpf_prog_array_free_sleepable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_prog_array_free_sleepable(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea350)
Location: kernel/bpf/core.c:2283
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff812ea350-ffffffff812ea386: bpf_prog_array_free_sleepable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_prog_array_free_sleepable(struct bpf_prog_array *progs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308660)
Location: kernel/bpf/core.c:2459
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog
  - kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog
```
**Symbols:**

```
ffffffff81308660-ffffffff81308696: bpf_prog_array_free_sleepable (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
