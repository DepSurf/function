# Function: <code>perf_aux_output_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size, bool truncated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81185960)
Location: kernel/events/ring_buffer.c:346
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_del
  - arch/x86/events/intel/bts.c:bts_event_add
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/pt.c:pt_event_add
  - arch/x86/events/intel/pt.c:pt_event_del
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81185960-ffffffff81185a48: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size, bool truncated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81197f20)
Location: kernel/events/ring_buffer.c:411
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81197f20-ffffffff81198028: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size, bool truncated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811a7900)
Location: kernel/events/ring_buffer.c:411
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff811a7900-ffffffff811a7a08: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811af080)
Location: kernel/events/ring_buffer.c:425
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff811af080-ffffffff811af1a9: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c2c10)
Location: kernel/events/ring_buffer.c:439
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff811c2c10-ffffffff811c2d64: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e2fc0)
Location: kernel/events/ring_buffer.c:440
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff811e2fc0-ffffffff811e30fd: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f3430)
Location: kernel/events/ring_buffer.c:440
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff811f3430-ffffffff811f3582: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120b120)
Location: kernel/events/ring_buffer.c:475
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8120b120-ffffffff8120b272: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81218400)
Location: kernel/events/ring_buffer.c:475
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81218400-ffffffff81218552: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81243f70)
Location: kernel/events/ring_buffer.c:475
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81243f70-ffffffff812440b7: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124e600)
Location: kernel/events/ring_buffer.c:477
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8124e600-ffffffff8124e747: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81252f00)
Location: kernel/events/ring_buffer.c:477
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81252f00-ffffffff81253042: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8128e7f0)
Location: kernel/events/ring_buffer.c:477
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8128e7f0-ffffffff8128e932: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e36d0)
Location: kernel/events/ring_buffer.c:477
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff812e36d0-ffffffff812e3823: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134bd70)
Location: kernel/events/ring_buffer.c:480
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8134bd70-ffffffff8134bec3: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137cdc0)
Location: kernel/events/ring_buffer.c:480
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8137cdc0-ffffffff8137cf13: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a6020)
Location: kernel/events/ring_buffer.c:481
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff813a6020-ffffffff813a6173: perf_aux_output_end (STB_GLOBAL)
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
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a2e98)
Location: kernel/events/ring_buffer.c:475
Inline: False
```
**Symbols:**

```
ffff8000102a2e98-ffff8000102a2fc4: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c04d29f0)
Location: kernel/events/ring_buffer.c:475
Inline: False
```
**Symbols:**

```
c04d29f0-c04d2b44: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c000000000355210)
Location: kernel/events/ring_buffer.c:475
Inline: False
```
**Symbols:**

```
c000000000355210-c00000000035537c: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d0dd8)
Location: kernel/events/ring_buffer.c:475
Inline: False
```
**Symbols:**

```
ffffffe0001d0dd8-ffffffe0001d0ef8: perf_aux_output_end (STB_GLOBAL)
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
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81210a50)
Location: kernel/events/ring_buffer.c:475
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff81210a50-ffffffff81210ba2: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812037e0)
Location: kernel/events/ring_buffer.c:475
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff812037e0-ffffffff81203932: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120e7f0)
Location: kernel/events/ring_buffer.c:475
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8120e7f0-ffffffff8120e942: perf_aux_output_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_aux_output_end(struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121d700)
Location: kernel/events/ring_buffer.c:475
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:intel_bts_interrupt
  - arch/x86/events/intel/bts.c:bts_event_stop
  - arch/x86/events/intel/bts.c:bts_event_start
  - arch/x86/events/intel/pt.c:pt_event_stop
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
```
**Symbols:**

```
ffffffff8121d700-ffffffff8121d852: perf_aux_output_end (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool truncated</code>
</li>
</ul>
</details>
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
