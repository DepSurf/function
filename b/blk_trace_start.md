# Function: <code>blk_trace_start</code>

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
int blk_trace_start(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812841a0)
Location: kernel/trace/blktrace.c:349
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_startstop
```
**Symbols:**

```
ffffffff812841a0-ffffffff81284225: blk_trace_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_trace_start(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812a0e50)
Location: kernel/trace/blktrace.c:349
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_startstop
```
**Symbols:**

```
ffffffff812a0e50-ffffffff812a0ed5: blk_trace_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_trace_start(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812bc580)
Location: kernel/trace/blktrace.c:349
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_startstop
```
**Symbols:**

```
ffffffff812bc580-ffffffff812bc605: blk_trace_start (STB_LOCAL)
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
