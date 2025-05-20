# Function: <code>traceprobe_probes_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t traceprobe_probes_write(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8116e4a0)
Location: kernel/trace/trace_probe.c:609
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff8116e4a0-ffffffff8116e5bd: traceprobe_probes_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t traceprobe_probes_write(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8117bb10)
Location: kernel/trace/trace_probe.c:642
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff8117bb10-ffffffff8117bc4a: traceprobe_probes_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t traceprobe_probes_write(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81187720)
Location: kernel/trace/trace_probe.c:646
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff81187720-ffffffff8118785a: traceprobe_probes_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t traceprobe_probes_write(struct file *file, const char *buffer, size_t count, loff_t *ppos, int (*createfn)(int, char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8118a3a0)
Location: kernel/trace/trace_probe.c:647
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_write
  - kernel/trace/trace_uprobe.c:probes_write
```
**Symbols:**

```
ffffffff8118a3a0-ffffffff8118a4f7: traceprobe_probes_write (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
