# Function: <code>set_print_fmt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8116e5c0)
Location: kernel/trace/trace_probe.c:707
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8116e5c0-ffffffff8116e61f: set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8117bc50)
Location: kernel/trace/trace_probe.c:740
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8117bc50-ffffffff8117bcaf: set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81187860)
Location: kernel/trace/trace_probe.c:744
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81187860-ffffffff811878bf: set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8118a500)
Location: kernel/trace/trace_probe.c:756
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8118a500-ffffffff8118a55f: set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81197fb0)
Location: kernel/trace/trace_probe.c:668
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81197fb0-ffffffff8119800f: set_print_fmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_print_fmt(struct trace_probe *tp, bool is_return);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811ad770)
Location: kernel/trace/trace_probe.c:668
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811ad770-ffffffff811ad7cf: set_print_fmt (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
