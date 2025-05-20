# Function: <code>trace_event_raw_event_alloc_vmap_area</code>

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
void trace_event_raw_event_alloc_vmap_area(void *__data, long unsigned int addr, long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813db790)
Location: include/trace/events/vmalloc.h:23
Inline: False
```
**Symbols:**

```
ffffffff813db790-ffffffff813db871: trace_event_raw_event_alloc_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_alloc_vmap_area(void *__data, long unsigned int addr, long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8140ff20)
Location: include/trace/events/vmalloc.h:23
Inline: False
```
**Symbols:**

```
ffffffff8140ff20-ffffffff81410001: trace_event_raw_event_alloc_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_alloc_vmap_area(void *__data, long unsigned int addr, long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143c880)
Location: include/trace/events/vmalloc.h:23
Inline: False
```
**Symbols:**

```
ffffffff8143c880-ffffffff8143c961: trace_event_raw_event_alloc_vmap_area (STB_LOCAL)
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
