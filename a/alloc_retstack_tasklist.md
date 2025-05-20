# Function: <code>alloc_retstack_tasklist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81145d48)
Location: kernel/trace/ftrace.c:5665
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114e582)
Location: kernel/trace/ftrace.c:5699
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811584c4)
Location: kernel/trace/ftrace.c:5748
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115b81c)
Location: kernel/trace/ftrace.c:6529
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811688ec)
Location: kernel/trace/ftrace.c:6828
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811775c0)
Location: kernel/trace/ftrace.c:6814
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a0934)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811ae70b)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b9e8b)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_retstack_tasklist(struct ftrace_ret_stack **ret_stack_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d28a0)
Location: kernel/trace/fgraph.c:370
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811d28a0-ffffffff811d29db: alloc_retstack_tasklist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_retstack_tasklist(struct ftrace_ret_stack **ret_stack_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811cf9f0)
Location: kernel/trace/fgraph.c:369
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
**Symbols:**

```
ffffffff811cf9f0-ffffffff811cfb44: alloc_retstack_tasklist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d10f2)
Location: kernel/trace/fgraph.c:369
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811fddf2)
Location: kernel/trace/fgraph.c:369
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff81238753)
Location: kernel/trace/fgraph.c:380
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812855f3)
Location: kernel/trace/fgraph.c:380
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812a22a5)
Location: kernel/trace/fgraph.c:405
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812bda3b)
Location: kernel/trace/fgraph.c:405
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffff800010238620)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0474244)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0000000002c4a40)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffe00018f5bc)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b24ab)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a52bb)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b027b)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811be2c0)
Location: kernel/trace/fgraph.c:342
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
