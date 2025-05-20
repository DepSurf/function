# Function: <code>ftrace_graph_notrace_addr</code>

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
In kernel/trace/trace_functions_graph.c (ffffffff81159315)
Location: kernel/trace/trace.h:787
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_functions_graph.c (ffffffff81163ebb)
Location: kernel/trace/trace.h:816
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c465)
Location: kernel/trace/trace.h:824
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8116f223)
Location: kernel/trace/trace.h:824
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8116f7a5)
Location: kernel/trace/trace.h:867
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81172449)
Location: kernel/trace/trace.h:867
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8117c895)
Location: kernel/trace/trace.h:869
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8117f5e9)
Location: kernel/trace/trace.h:869
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8118b9a5)
Location: kernel/trace/trace.h:875
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e6d9)
Location: kernel/trace/trace.h:875
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8119938c)
Location: kernel/trace/trace.h:936
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119bd87)
Location: kernel/trace/trace.h:936
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811a6f91)
Location: kernel/trace/trace.h:982
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a99a6)
Location: kernel/trace/trace.h:982
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2781)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b5196)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811cbac1)
Location: kernel/trace/trace.h:1048
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cdec6)
Location: kernel/trace/trace.h:1048
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811c91a1)
Location: kernel/trace/trace.h:897
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb3a6)
Location: kernel/trace/trace.h:897
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9db1)
Location: kernel/trace/trace.h:900
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cc6b9)
Location: kernel/trace/trace.h:900
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5941)
Location: kernel/trace/trace.h:906
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f8dcd)
Location: kernel/trace/trace.h:906
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f765)
Location: kernel/trace/trace.h:914
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232bb5)
Location: kernel/trace/trace.h:914
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b8e5)
Location: kernel/trace/trace.h:913
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f30c)
Location: kernel/trace/trace.h:913
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff81293405)
Location: kernel/trace/trace.h:935
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129be9c)
Location: kernel/trace/trace.h:935
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae3e5)
Location: kernel/trace/trace.h:953
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b757c)
Location: kernel/trace/trace.h:953
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffff800010231594)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffff80001023300c)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (c046c39c)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c046ed50)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (c0000000002ba80c)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c0000000002bde60)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffe0001885ae)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a622)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811aada1)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ad7b6)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8119dcf1)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a0632)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8b71)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab586)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6965)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b93f1)
Location: kernel/trace/trace.h:992
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
</details>
</li>
</ul>

## Differences
