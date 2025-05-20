# Function: <code>trace_parser_clear</code>

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
In kernel/trace/ftrace.c (ffffffff81142413)
Location: kernel/trace/trace.h:898
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8114df6e)
Location: kernel/trace/trace.h:898
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
```
```
In kernel/trace/trace_events.c (ffffffff8115f317)
Location: kernel/trace/trace.h:898
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_pid_write
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
In kernel/trace/ftrace.c (ffffffff8114c6ad)
Location: kernel/trace/trace.h:929
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8115696e)
Location: kernel/trace/trace.h:929
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff8115659a)
Location: kernel/trace/trace.h:948
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81161aae)
Location: kernel/trace/trace.h:948
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff81159ce4)
Location: kernel/trace/trace.h:1061
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff81164ea0)
Location: kernel/trace/trace.h:1061
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff811667e4)
Location: kernel/trace/trace.h:1063
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff81171df0)
Location: kernel/trace/trace.h:1063
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff811754f3)
Location: kernel/trace/trace.h:1069
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff81180f72)
Location: kernel/trace/trace.h:1069
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff81183133)
Location: kernel/trace/trace.h:1132
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff8118e932)
Location: kernel/trace/trace.h:1132
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff8118fea1)
Location: kernel/trace/trace.h:1178
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff8119c341)
Location: kernel/trace/trace.h:1178
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff8119be71)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff811a7d31)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff811b0f31)
Location: kernel/trace/trace.h:1264
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff811c00d6)
Location: kernel/trace/trace.h:1264
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff811ae9a1)
Location: kernel/trace/trace.h:1120
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff811bdd06)
Location: kernel/trace/trace.h:1120
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff811af351)
Location: kernel/trace/trace.h:1123
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff811bd816)
Location: kernel/trace/trace.h:1123
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff811d9192)
Location: kernel/trace/trace.h:1129
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff811e8343)
Location: kernel/trace/trace.h:1129
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff8120fec4)
Location: kernel/trace/trace.h:1137
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff8121feb3)
Location: kernel/trace/trace.h:1137
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff81259294)
Location: kernel/trace/trace.h:1136
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff8126ab93)
Location: kernel/trace/trace.h:1136
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff81270664)
Location: kernel/trace/trace.h:1158
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff81281d13)
Location: kernel/trace/trace.h:1158
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff8128aae4)
Location: kernel/trace/trace.h:1176
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff8129ce93)
Location: kernel/trace/trace.h:1176
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffff800010214cd4)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffff800010224384)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (c0453a44)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (c0461b0c)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (c00000000029619c)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (c0000000002a9394)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffe000174b36)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffe00017f87a)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff81194491)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff811a0351)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff811875a1)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff81193361)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff81192261)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff8119e121)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
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
In kernel/trace/ftrace.c (ffffffff8119fdf1)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
```
```
In kernel/trace/trace.c (ffffffff811abe01)
Location: kernel/trace/trace.h:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_pid_write
```
</details>
</li>
</ul>

## Differences
