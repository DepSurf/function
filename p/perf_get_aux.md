# Function: <code>perf_get_aux</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81185770)
Location: kernel/events/ring_buffer.c:416
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_event_del
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_del
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81185770-ffffffff81185790: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81197a10)
Location: kernel/events/ring_buffer.c:490
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff81197a10-ffffffff81197a30: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811a7400)
Location: kernel/events/ring_buffer.c:490
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff811a7400-ffffffff811a7420: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811aebc0)
Location: kernel/events/ring_buffer.c:502
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff811aebc0-ffffffff811aebe0: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c1c70)
Location: kernel/events/ring_buffer.c:512
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff811c1c70-ffffffff811c1c90: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e2060)
Location: kernel/events/ring_buffer.c:513
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff811e2060-ffffffff811e2080: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f24d0)
Location: kernel/events/ring_buffer.c:523
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff811f24d0-ffffffff811f24ee: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120a190)
Location: kernel/events/ring_buffer.c:555
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff8120a190-ffffffff8120a1ae: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81217470)
Location: kernel/events/ring_buffer.c:555
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff81217470-ffffffff8121748e: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81242e40)
Location: kernel/events/ring_buffer.c:555
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff81242e40-ffffffff81242e5e: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124d520)
Location: kernel/events/ring_buffer.c:557
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_config
```
**Symbols:**

```
ffffffff8124d520-ffffffff8124d53e: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81251e60)
Location: kernel/events/ring_buffer.c:557
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff81251e60-ffffffff81251e7e: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8128d6e0)
Location: kernel/events/ring_buffer.c:557
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff8128d6e0-ffffffff8128d6fe: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e2460)
Location: kernel/events/ring_buffer.c:557
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff812e2460-ffffffff812e2484: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134aa00)
Location: kernel/events/ring_buffer.c:560
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff8134aa00-ffffffff8134aa24: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137ba40)
Location: kernel/events/ring_buffer.c:560
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff8137ba40-ffffffff8137ba64: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a4c80)
Location: kernel/events/ring_buffer.c:561
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_snapshot_aux
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff813a4c80-ffffffff813a4ca4: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a1d00)
Location: kernel/events/ring_buffer.c:555
Inline: False
```
**Symbols:**

```
ffff8000102a1d00-ffff8000102a1d34: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c04d1838)
Location: kernel/events/ring_buffer.c:555
Inline: False
```
**Symbols:**

```
c04d1838-c04d1864: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c000000000353b50)
Location: kernel/events/ring_buffer.c:555
Inline: False
```
**Symbols:**

```
c000000000353b50-c000000000353b74: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d09a4)
Location: kernel/events/ring_buffer.c:555
Inline: False
```
**Symbols:**

```
ffffffe0001d09a4-ffffffe0001d09cc: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120fac0)
Location: kernel/events/ring_buffer.c:555
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff8120fac0-ffffffff8120fade: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81202850)
Location: kernel/events/ring_buffer.c:555
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff81202850-ffffffff8120286e: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120d860)
Location: kernel/events/ring_buffer.c:555
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff8120d860-ffffffff8120d87e: perf_get_aux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *perf_get_aux(struct perf_output_handle *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121c700)
Location: kernel/events/ring_buffer.c:555
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_update
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
```
**Symbols:**

```
ffffffff8121c700-ffffffff8121c71e: perf_get_aux (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
