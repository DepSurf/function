# Function: <code>notify_new_max_latency</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void notify_new_max_latency(u64 latency);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_osnoise.c (ffffffff81295bc0)
Location: kernel/trace/trace_osnoise.c:1390
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:timerlat_irq
```
**Symbols:**

```
ffffffff81295bc0-ffffffff81295c33: notify_new_max_latency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void notify_new_max_latency(u64 latency);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_osnoise.c (ffffffff812b1230)
Location: kernel/trace/trace_osnoise.c:1390
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:timerlat_irq
```
**Symbols:**

```
ffffffff812b1230-ffffffff812b12a3: notify_new_max_latency (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
