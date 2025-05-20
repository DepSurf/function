# Function: <code>ring_buffer_time_stamp_abs</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811799ea)
Location: kernel/trace/ring_buffer.c:1451
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8117c220-ffffffff8117c228: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118930a)
Location: kernel/trace/ring_buffer.c:1499
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81189a20-ffffffff81189a28: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811968f9)
Location: kernel/trace/ring_buffer.c:1476
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81196ff0-ffffffff81196ff8: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a22c9)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811a29f0-ffffffff811a29f8: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b8c30)
Location: kernel/trace/ring_buffer.c:1480
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811b95d0-ffffffff811b95d8: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b663e)
Location: kernel/trace/ring_buffer.c:1727
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811b7010-ffffffff811b7018: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b595d)
Location: kernel/trace/ring_buffer.c:1810
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
```
**Symbols:**

```
ffffffff811b7aa0-ffffffff811b7aa8: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811df9b1)
Location: kernel/trace/ring_buffer.c:1810
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
```
**Symbols:**

```
ffffffff81cb4b34-ffffffff81cb4b54: ring_buffer_time_stamp_abs.cold (STB_LOCAL)
ffffffff811e1cd0-ffffffff811e1ce3: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81216cfa)
Location: kernel/trace/ring_buffer.c:1846
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
```
**Symbols:**

```
ffffffff81e65b5f-ffffffff81e65b89: ring_buffer_time_stamp_abs.cold (STB_LOCAL)
ffffffff81218a10-ffffffff81218a2d: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81261e6a)
Location: kernel/trace/ring_buffer.c:1908
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
```
**Symbols:**

```
ffffffff8205d266-ffffffff8205d290: ring_buffer_time_stamp_abs.cold (STB_LOCAL)
ffffffff81262940-ffffffff8126295d: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81278eda)
Location: kernel/trace/ring_buffer.c:1906
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
```
**Symbols:**

```
ffffffff820dbc24-ffffffff820dbc4e: ring_buffer_time_stamp_abs.cold (STB_LOCAL)
ffffffff81279920-ffffffff8127993d: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128e700)
Location: kernel/trace/ring_buffer.c:1747
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_max_event_size
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
```
**Symbols:**

```
ffffffff821b7a45-ffffffff821b7a6f: ring_buffer_time_stamp_abs.cold (STB_LOCAL)
ffffffff81294400-ffffffff8129441d: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021c6f0)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffff80001021cef8-ffff80001021cf00: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045b19c)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
c045ba00-c045ba14: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029fed0)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
c0000000002a0940-c0000000002a0948: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017a1bc)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffe00017a6f4-ffffffe00017a704: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119a8e9)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8119b010-ffffffff8119b018: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118d969)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8118e090-ffffffff8118e098: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811986b9)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81198de0-ffffffff81198de8: ring_buffer_time_stamp_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a6310)
Location: kernel/trace/ring_buffer.c:1477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
Direct callers:
  - kernel/trace/trace.c:tracing_time_stamp_mode_show
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811a6a50-ffffffff811a6a58: ring_buffer_time_stamp_abs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer *buffer</code> ➡️ <code>struct trace_buffer *buffer</code>
</li>
</ul>
</details>
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
