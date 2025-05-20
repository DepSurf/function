# Function: <code>trace_buffer_iter</code>

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
In kernel/trace/trace.c (ffffffff8114aefe)
Location: kernel/trace/trace.h:550
Inline: True
Inline callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:tracing_iter_reset
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81159ff4)
Location: kernel/trace/trace.h:550
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff81154488)
Location: kernel/trace/trace.h:559
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8116495c)
Location: kernel/trace/trace.h:559
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8115eac8)
Location: kernel/trace/trace.h:566
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8116fcd2)
Location: kernel/trace/trace.h:566
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff81161cf8)
Location: kernel/trace/trace.h:572
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81172e27)
Location: kernel/trace/trace.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8116edc8)
Location: kernel/trace/trace.h:576
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8117ffd7)
Location: kernel/trace/trace.h:576
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8117de34)
Location: kernel/trace/trace.h:584
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118f0ef)
Location: kernel/trace/trace.h:584
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8118b724)
Location: kernel/trace/trace.h:624
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119c8df)
Location: kernel/trace/trace.h:624
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff81198a74)
Location: kernel/trace/trace.h:673
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811aa5a9)
Location: kernel/trace/trace.h:673
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff811a4364)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b5d99)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff811bc19c)
Location: kernel/trace/trace.h:718
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cefe4)
Location: kernel/trace/trace.h:718
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff811b9dac)
Location: kernel/trace/trace.h:562
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cc4c4)
Location: kernel/trace/trace.h:562
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff811ba441)
Location: kernel/trace/trace.h:559
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cd7f7)
Location: kernel/trace/trace.h:559
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff811e4c74)
Location: kernel/trace/trace.h:565
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811fa0aa)
Location: kernel/trace/trace.h:565
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8121bfe7)
Location: kernel/trace/trace.h:573
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81234136)
Location: kernel/trace/trace.h:573
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff81265cc1)
Location: kernel/trace/trace.h:572
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81280966)
Location: kernel/trace/trace.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8127d031)
Location: kernel/trace/trace.h:591
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129d5bf)
Location: kernel/trace/trace.h:591
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff81297552)
Location: kernel/trace/trace.h:607
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b8c9f)
Location: kernel/trace/trace.h:607
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffff80001021f2f4)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffff800010233dd4)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (c045d758)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (c046f9b4)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (c0000000002a2c80)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (c0000000002bf0fc)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffe00017bd82)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018b506)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8119c984)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ae3b9)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8118f9e4)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a1209)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff8119a754)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ac189)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
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
In kernel/trace/trace.c (ffffffff811a83f4)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_poll
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:wait_on_pipe
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ba059)
Location: kernel/trace/trace.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
</details>
</li>
</ul>

## Differences
