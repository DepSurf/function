# Function: <code>__bpf_trace_mm_vmscan_inactive_list_is_low</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81205f00)
Location: include/trace/events/vmscan.h:429
Inline: False
```
**Symbols:**

```
ffffffff81205f00-ffffffff81205f1d: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812188d0)
Location: include/trace/events/vmscan.h:429
Inline: False
```
**Symbols:**

```
ffffffff812188d0-ffffffff812188ed: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812283b0)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
ffffffff812283b0-ffffffff812283cd: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81236250)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
ffffffff81236250-ffffffff8123626d: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812638e0)
Location: include/trace/events/vmscan.h:426
Inline: False
```
**Symbols:**

```
ffffffff812638e0-ffffffff812638fd: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126e270)
Location: include/trace/events/vmscan.h:426
Inline: False
```
**Symbols:**

```
ffffffff8126e270-ffffffff8126e28d: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81272f70)
Location: include/trace/events/vmscan.h:426
Inline: False
```
**Symbols:**

```
ffffffff81272f70-ffffffff81272f8d: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c6068)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
ffff8000102c6068-ffff8000102c6094: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f12a0)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
c04f12a0-c04f1314: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000382190)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
c000000000382190-c0000000003821cc: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e8a0)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
ffffffff8122e8a0-ffffffff8122e8bd: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81221960)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
ffffffff81221960-ffffffff8122197d: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122c640)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
ffffffff8122c640-ffffffff8122c65d: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mm_vmscan_inactive_list_is_low(void *__data, int nid, int reclaim_idx, long unsigned int total_inactive, long unsigned int inactive, long unsigned int total_active, long unsigned int active, long unsigned int ratio, int file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123ba30)
Location: include/trace/events/vmscan.h:422
Inline: False
```
**Symbols:**

```
ffffffff8123ba30-ffffffff8123ba4d: __bpf_trace_mm_vmscan_inactive_list_is_low (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
