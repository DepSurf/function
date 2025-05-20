# Function: <code>put_recursion_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81182da5)
Location: kernel/events/internal.h:210
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
```
```
In kernel/events/callchain.c (ffffffff8118632a)
Location: kernel/events/internal.h:210
Inline: True
Inline callers:
  - kernel/events/callchain.c:perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118b367)
Location: kernel/events/internal.h:229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff81198675)
Location: kernel/events/internal.h:229
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119abf7)
Location: kernel/events/internal.h:229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811a8055)
Location: kernel/events/internal.h:229
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a262a)
Location: kernel/events/internal.h:229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811af86b)
Location: kernel/events/internal.h:229
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b6782)
Location: kernel/events/internal.h:230
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811c33e9)
Location: kernel/events/internal.h:230
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d626f)
Location: kernel/events/internal.h:226
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811e378b)
Location: kernel/events/internal.h:226
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e6e12)
Location: kernel/events/internal.h:226
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811f3c59)
Location: kernel/events/internal.h:226
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe101)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8120b941)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b3b1)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff81218c21)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81237407)
Location: kernel/events/internal.h:228
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8124481c)
Location: kernel/events/internal.h:228
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124100c)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8124eecf)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_callchain_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81244dc5)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff812537df)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_callchain_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127fdd4)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8128f11f)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_callchain_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d4e71)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff812e4097)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_callchain_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133d633)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff8134c7e7)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_callchain_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136e801)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff8137d837)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_callchain_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813978f1)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_trace_run_bpf_submit
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff813a6a97)
Location: kernel/events/internal.h:224
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_callchain_entry
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a09d4)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_put_recursion_context
```
```
In kernel/events/callchain.c (ffff8000102a398c)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d0ae0)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (c04d3160)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003525b0)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (c000000000355ef0)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5de4)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffe0001d1fd4)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812039d1)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff81211271)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f6ad1)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff81204001)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812017a1)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8120f011)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210b2b)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8121df21)
Location: kernel/events/internal.h:227
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
</ul>

## Differences
