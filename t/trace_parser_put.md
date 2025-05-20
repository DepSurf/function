# Function: <code>trace_parser_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114df50)
Location: kernel/trace/trace.c:914
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff8114df50-ffffffff8114df5f: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156cdb)
Location: kernel/trace/trace.c:1149
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff81156950-ffffffff8115695f: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161e1b)
Location: kernel/trace/trace.c:1193
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_write
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff81161a90-ffffffff81161a9f: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116521f)
Location: kernel/trace/trace.c:1191
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff81164e70-ffffffff81164e8c: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117216f)
Location: kernel/trace/trace.c:1191
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff81171dc0-ffffffff81171ddc: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118131f)
Location: kernel/trace/trace.c:1198
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff81180f40-ffffffff81180f5c: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118ecdf)
Location: kernel/trace/trace.c:1199
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff8118e900-ffffffff8118e91c: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c62f)
Location: kernel/trace/trace.c:1370
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff8119c310-ffffffff8119c32c: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a801f)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff811a7d00-ffffffff811a7d1c: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c03c1)
Location: kernel/trace/trace.c:1423
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff811c00a0-ffffffff811c00bf: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be03f)
Location: kernel/trace/trace.c:1574
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff811bdcd0-ffffffff811bdcef: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bdb65)
Location: kernel/trace/trace.c:1571
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff811bd7e0-ffffffff811bd7ff: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e86b5)
Location: kernel/trace/trace.c:1586
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff811e8300-ffffffff811e831f: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8122017a)
Location: kernel/trace/trace.c:1577
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff8121fe60-ffffffff8121fe85: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126aeaa)
Location: kernel/trace/trace.c:1583
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff8126ab30-ffffffff8126ab55: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8128201a)
Location: kernel/trace/trace.c:1634
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff81281cb0-ffffffff81281cd5: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129d19a)
Location: kernel/trace/trace.c:1644
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff8129ce30-ffffffff8129ce55: trace_parser_put (STB_GLOBAL)
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
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010224a44)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffff800010224350-ffff800010224378: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0461f0c)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
c0461abc-c0461ae0: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a9978)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
c0000000002a9330-c0000000002a9374: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017fbb0)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffe00017f84c-ffffffe00017f870: trace_parser_put (STB_GLOBAL)
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
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a063f)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff811a0320-ffffffff811a033c: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119364f)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff81193330-ffffffff8119334c: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119e40f)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff8119e0f0-ffffffff8119e10c: trace_parser_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void trace_parser_put(struct trace_parser *parser);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac0ef)
Location: kernel/trace/trace.c:1388
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_write
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:ftrace_event_write
```
**Symbols:**

```
ffffffff811abdd0-ffffffff811abdec: trace_parser_put (STB_GLOBAL)
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
