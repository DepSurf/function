# Function: <code>trace_event_raw_event_mm_vmscan_lru_isolate_template</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_event_raw_event_mm_vmscan_lru_isolate_template(void *__data, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_taken, isolate_mode_t isolate_mode, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a1eb0)
Location: include/trace/events/vmscan.h:267
Inline: False
```
**Symbols:**

```
ffffffff811a1eb0-ffffffff811a1f9a: trace_event_raw_event_mm_vmscan_lru_isolate_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void trace_event_raw_event_mm_vmscan_lru_isolate_template(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_taken, isolate_mode_t isolate_mode, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b7950)
Location: include/trace/events/vmscan.h:272
Inline: False
```
**Symbols:**

```
ffffffff811b7950-ffffffff811b7a48: trace_event_raw_event_mm_vmscan_lru_isolate_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_event_raw_event_mm_vmscan_lru_isolate_template(void *__data, int classzone_idx, int order, long unsigned int nr_requested, long unsigned int nr_scanned, long unsigned int nr_taken, isolate_mode_t isolate_mode, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c7f60)
Location: include/trace/events/vmscan.h:272
Inline: False
```
**Symbols:**

```
ffffffff811c7f60-ffffffff811c8058: trace_event_raw_event_mm_vmscan_lru_isolate_template (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int classzone_idx</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, order, nr_requested, nr_scanned, nr_taken, isolate_mode, file</code> ➡️ <code>__data, classzone_idx, order, nr_requested, nr_scanned, nr_taken, isolate_mode, file</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
