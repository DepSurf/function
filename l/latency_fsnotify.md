# Function: <code>latency_fsnotify</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void latency_fsnotify(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c092a)
Location: kernel/trace/trace.c:1580
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff811c04d0-ffffffff811c04ed: latency_fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void latency_fsnotify(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be553)
Location: kernel/trace/trace.c:1730
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff811be140-ffffffff811be15d: latency_fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void latency_fsnotify(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bbaea)
Location: kernel/trace/trace.c:1727
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff811bdc50-ffffffff811bdc6d: latency_fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void latency_fsnotify(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e61fc)
Location: kernel/trace/trace.c:1742
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff811e87a0-ffffffff811e87bd: latency_fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void latency_fsnotify(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121dec5)
Location: kernel/trace/trace.c:1733
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff812202f0-ffffffff8122031d: latency_fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void latency_fsnotify(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81268582)
Location: kernel/trace/trace.c:1741
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
```
**Symbols:**

```
ffffffff8126b030-ffffffff8126b05d: latency_fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void latency_fsnotify(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127f742)
Location: kernel/trace/trace.c:1792
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_osnoise.c:notify_new_max_latency
```
**Symbols:**

```
ffffffff812821a0-ffffffff812821cd: latency_fsnotify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void latency_fsnotify(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81299f22)
Location: kernel/trace/trace.c:1802
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_osnoise.c:notify_new_max_latency
```
**Symbols:**

```
ffffffff8129d320-ffffffff8129d34d: latency_fsnotify (STB_GLOBAL)
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
