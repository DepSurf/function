# Function: <code>ftrace_graph_addr</code>

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
In kernel/trace/trace_functions_graph.c (ffffffff811596d7)
Location: kernel/trace/trace.h:762
Inline: True
Inline callers:
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
In kernel/trace/trace_functions_graph.c (ffffffff81163fba)
Location: kernel/trace/trace.h:791
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c4e9)
Location: kernel/trace/trace.h:799
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8116f30e)
Location: kernel/trace/trace.h:799
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8116f7c0)
Location: kernel/trace/trace.h:838
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8117246f)
Location: kernel/trace/trace.h:838
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8117c8b0)
Location: kernel/trace/trace.h:840
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8117f60f)
Location: kernel/trace/trace.h:840
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8118b9c0)
Location: kernel/trace/trace.h:846
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e77b)
Location: kernel/trace/trace.h:846
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811993a8)
Location: kernel/trace/trace.h:891
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119be30)
Location: kernel/trace/trace.h:891
Inline: True
Inline callers:
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811a6fad)
Location: kernel/trace/trace.h:937
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a9aad)
Location: kernel/trace/trace.h:937
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811b279d)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b529d)
Location: kernel/trace/trace.h:938
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811cbadd)
Location: kernel/trace/trace.h:994
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cdfce)
Location: kernel/trace/trace.h:994
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811c91bd)
Location: kernel/trace/trace.h:843
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb4ae)
Location: kernel/trace/trace.h:843
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9dcd)
Location: kernel/trace/trace.h:846
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cc7c8)
Location: kernel/trace/trace.h:846
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811f595d)
Location: kernel/trace/trace.h:852
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f8ef0)
Location: kernel/trace/trace.h:852
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f7b9)
Location: kernel/trace/trace.h:860
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232d00)
Location: kernel/trace/trace.h:860
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b939)
Location: kernel/trace/trace.h:859
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f45d)
Location: kernel/trace/trace.h:859
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
In kernel/trace/trace_sched_wakeup.c (ffffffff81293459)
Location: kernel/trace/trace.h:881
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129bfed)
Location: kernel/trace/trace.h:881
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
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae439)
Location: kernel/trace/trace.h:899
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b76cd)
Location: kernel/trace/trace.h:899
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
In kernel/trace/trace_sched_wakeup.c (ffff8000102315ac)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffff800010233140)
Location: kernel/trace/trace.h:938
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
In kernel/trace/trace_sched_wakeup.c (c046c3bc)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c046eeb8)
Location: kernel/trace/trace.h:938
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
In kernel/trace/trace_sched_wakeup.c (c0000000002ba840)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c0000000002be000)
Location: kernel/trace/trace.h:938
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
In kernel/trace/trace_sched_wakeup.c (ffffffe0001885ce)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a5c8)
Location: kernel/trace/trace.h:938
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811aadbd)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ad8bd)
Location: kernel/trace/trace.h:938
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
In kernel/trace/trace_sched_wakeup.c (ffffffff8119dd0d)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a071c)
Location: kernel/trace/trace.h:938
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8b8d)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab68d)
Location: kernel/trace/trace.h:938
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811b69e7)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b9526)
Location: kernel/trace/trace.h:938
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
</details>
</li>
</ul>

## Differences
