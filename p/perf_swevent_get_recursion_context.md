# Function: <code>perf_swevent_get_recursion_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117b050)
Location: kernel/events/core.c:6688
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:__perf_sw_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_prepare
```
**Symbols:**

```
ffffffff8117b050-ffffffff8117b0c0: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81196437)
Location: kernel/events/core.c:7282
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff8118c540-ffffffff8118c5ac: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a5eb7)
Location: kernel/events/core.c:7395
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff8119bb20-ffffffff8119bb8c: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ad637)
Location: kernel/events/core.c:7618
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff811a34f0-ffffffff811a355c: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811c11a7)
Location: kernel/events/core.c:7615
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff811b74c0-ffffffff811b752c: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e1517)
Location: kernel/events/core.c:7997
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff811d6ed0-ffffffff811d6f3c: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f1977)
Location: kernel/events/core.c:8006
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff811e72f0-ffffffff811e736a: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209537)
Location: kernel/events/core.c:8310
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff811fe920-ffffffff811fe993: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812168a7)
Location: kernel/events/core.c:8426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff8120b980-ffffffff8120b9f3: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812427a7)
Location: kernel/events/core.c:8976
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff81232e40-ffffffff81232eb3: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124cf0a)
Location: kernel/events/core.c:9242
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff8123c680-ffffffff8123c6d6: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8125160a)
Location: kernel/events/core.c:9372
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff81240de0-ffffffff81240e36: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128c40a)
Location: kernel/events/core.c:9491
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff8127b7d0-ffffffff8127b826: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e0fa6)
Location: kernel/events/core.c:9426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff812cf4b0-ffffffff812cf525: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813494a6)
Location: kernel/events/core.c:9751
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff81337f70-ffffffff81337fe5: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137a4b6)
Location: kernel/events/core.c:9780
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff81368d90-ffffffff81368e05: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a36b6)
Location: kernel/events/core.c:9850
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff81391c70-ffffffff81391ce5: perf_swevent_get_recursion_context (STB_GLOBAL)
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
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010294ec8)
Location: kernel/events/core.c:8426
Inline: False
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffff800010294ec8-ffff800010294f3c: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d0ebc)
Location: kernel/events/core.c:8426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
c04c5108-c04c5198: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000352ab4)
Location: kernel/events/core.c:8426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
c000000000342bc0-c000000000342c58: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cfeee)
Location: kernel/events/core.c:8426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffe0001c6900-ffffffe0001c6976: perf_swevent_get_recursion_context (STB_GLOBAL)
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
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120eef7)
Location: kernel/events/core.c:8426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff81203fa0-ffffffff81204013: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201ca7)
Location: kernel/events/core.c:8426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff811f6d30-ffffffff811f6da3: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120cc97)
Location: kernel/events/core.c:8426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff81201d70-ffffffff81201de3: perf_swevent_get_recursion_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int perf_swevent_get_recursion_context();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121bb1e)
Location: kernel/events/core.c:8426
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
```
**Symbols:**

```
ffffffff81211440-ffffffff812114b3: perf_swevent_get_recursion_context (STB_GLOBAL)
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
