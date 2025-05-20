# Function: <code>kprobe_multi_link_prog_run</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812574ae)
Location: kernel/trace/bpf_trace.c:2388
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a6e8e)
Location: kernel/trace/bpf_trace.c:2623
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c8f30)
Location: kernel/trace/bpf_trace.c:2632
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_exit_handler
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
```
**Symbols:**

```
ffffffff812c8f30-ffffffff812c902b: kprobe_multi_link_prog_run.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e5f60)
Location: kernel/trace/bpf_trace.c:2779
Inline: True
Direct callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_exit_handler
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
```
**Symbols:**

```
ffffffff812e5f60-ffffffff812e606a: kprobe_multi_link_prog_run.isra.0 (STB_LOCAL)
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
