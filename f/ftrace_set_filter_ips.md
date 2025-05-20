# Function: <code>ftrace_set_filter_ips</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int ftrace_set_filter_ips(struct ftrace_ops *ops, long unsigned int *ips, unsigned int cnt, int remove, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120f210)
Location: kernel/trace/ftrace.c:5803
Inline: False
Direct callers:
  - kernel/trace/fprobe.c:register_fprobe_ips
```
**Symbols:**

```
ffffffff8120f210-ffffffff8120f296: ftrace_set_filter_ips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_set_filter_ips(struct ftrace_ops *ops, long unsigned int *ips, unsigned int cnt, int remove, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81258580)
Location: kernel/trace/ftrace.c:5875
Inline: False
Direct callers:
  - kernel/trace/fprobe.c:register_fprobe_ips
```
**Symbols:**

```
ffffffff81258580-ffffffff81258606: ftrace_set_filter_ips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ftrace_set_filter_ips(struct ftrace_ops *ops, long unsigned int *ips, unsigned int cnt, int remove, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126fb70)
Location: kernel/trace/ftrace.c:5659
Inline: False
Direct callers:
  - kernel/trace/fprobe.c:register_fprobe_ips
```
**Symbols:**

```
ffffffff8126fb70-ffffffff8126fbf6: ftrace_set_filter_ips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ftrace_set_filter_ips(struct ftrace_ops *ops, long unsigned int *ips, unsigned int cnt, int remove, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128a020)
Location: kernel/trace/ftrace.c:5663
Inline: False
Direct callers:
  - kernel/trace/fprobe.c:register_fprobe_ips
```
**Symbols:**

```
ffffffff8128a020-ffffffff8128a0a6: ftrace_set_filter_ips (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
