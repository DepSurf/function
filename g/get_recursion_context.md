# Function: <code>get_recursion_context</code>

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
In kernel/events/core.c (ffffffff8117b063)
Location: kernel/events/internal.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:__perf_sw_event
```
```
In kernel/events/callchain.c (ffffffff8118627e)
Location: kernel/events/internal.h:188
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
In kernel/events/core.c (ffffffff81196449)
Location: kernel/events/internal.h:207
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8119856e)
Location: kernel/events/internal.h:207
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
In kernel/events/core.c (ffffffff811a5ec9)
Location: kernel/events/internal.h:207
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811a7f4e)
Location: kernel/events/internal.h:207
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
In kernel/events/core.c (ffffffff811ad649)
Location: kernel/events/internal.h:207
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811af69e)
Location: kernel/events/internal.h:207
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
In kernel/events/core.c (ffffffff811c11b9)
Location: kernel/events/internal.h:208
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811c322e)
Location: kernel/events/internal.h:208
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
In kernel/events/core.c (ffffffff811e1535)
Location: kernel/events/internal.h:204
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811e35ce)
Location: kernel/events/internal.h:204
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
In kernel/events/core.c (ffffffff811f198d)
Location: kernel/events/internal.h:204
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff811f3a8e)
Location: kernel/events/internal.h:204
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
In kernel/events/core.c (ffffffff81209555)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8120b783)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (ffffffff812168c5)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff81218a63)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (ffffffff812427c5)
Location: kernel/events/internal.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff81244458)
Location: kernel/events/internal.h:206
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
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
In kernel/events/core.c (ffffffff8124cf1c)
Location: kernel/events/internal.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8124ed4b)
Location: kernel/events/internal.h:206
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8125161c)
Location: kernel/events/internal.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8125365b)
Location: kernel/events/internal.h:206
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8128c41c)
Location: kernel/events/internal.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8128ef9b)
Location: kernel/events/internal.h:206
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff812e0fc2)
Location: kernel/events/internal.h:211
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff812e3ee1)
Location: kernel/events/internal.h:211
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff813494c2)
Location: kernel/events/internal.h:211
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff8134c611)
Location: kernel/events/internal.h:211
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8137a4d2)
Location: kernel/events/internal.h:211
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff8137d661)
Location: kernel/events/internal.h:211
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff813a36d2)
Location: kernel/events/internal.h:211
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff813a68c1)
Location: kernel/events/internal.h:211
Inline: True
Inline callers:
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
In kernel/events/core.c (ffff800010294ee4)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_get_recursion_context
```
```
In kernel/events/callchain.c (ffff8000102a384c)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (c04d0ee4)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (c04d3040)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (c000000000352ad8)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (c000000000355c80)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (ffffffe0001cfefa)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffe0001d1e58)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (ffffffff8120ef15)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff812110b3)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (ffffffff81201cc5)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff81203e43)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (ffffffff8120ccb5)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8120ee53)
Location: kernel/events/internal.h:205
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
In kernel/events/core.c (ffffffff8121bb3c)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff8121dd63)
Location: kernel/events/internal.h:205
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
</ul>

## Differences
