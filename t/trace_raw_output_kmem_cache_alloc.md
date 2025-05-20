# Function: <code>trace_raw_output_kmem_cache_alloc</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_kmem_cache_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: include/trace/events/kmem.h:12
Inline: False
```
**Symbols:**

```
ffffffff813a07b0-ffffffff813a0881: trace_raw_output_kmem_cache_alloc (STB_LOCAL)
ffffffff8206319f-ffffffff820631b4: trace_raw_output_kmem_cache_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_kmem_cache_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: include/trace/events/kmem.h:12
Inline: False
```
**Symbols:**

```
ffffffff813d3a70-ffffffff813d3b41: trace_raw_output_kmem_cache_alloc (STB_LOCAL)
ffffffff820e2a3c-ffffffff820e2a51: trace_raw_output_kmem_cache_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_kmem_cache_alloc(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: include/trace/events/kmem.h:12
Inline: False
```
**Symbols:**

```
ffffffff813fe7f0-ffffffff813fe8c1: trace_raw_output_kmem_cache_alloc (STB_LOCAL)
ffffffff821bf42d-ffffffff821bf442: trace_raw_output_kmem_cache_alloc.cold (STB_LOCAL)
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
