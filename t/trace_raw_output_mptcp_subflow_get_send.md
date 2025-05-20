# Function: <code>trace_raw_output_mptcp_subflow_get_send</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum print_line_t trace_raw_output_mptcp_subflow_get_send(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baa040)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff81baa040-ffffffff81baa0af: trace_raw_output_mptcp_subflow_get_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mptcp_subflow_get_send(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff81c77680-ffffffff81c7770d: trace_raw_output_mptcp_subflow_get_send (STB_LOCAL)
ffffffff81d4320f-ffffffff81d4326b: trace_raw_output_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mptcp_subflow_get_send(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff81e1c6b0-ffffffff81e1c74f: trace_raw_output_mptcp_subflow_get_send (STB_LOCAL)
ffffffff81f0fcef-ffffffff81f0fd4b: trace_raw_output_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mptcp_subflow_get_send(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff81ff3dd0-ffffffff81ff3e6f: trace_raw_output_mptcp_subflow_get_send (STB_LOCAL)
ffffffff820b6095-ffffffff820b60f1: trace_raw_output_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mptcp_subflow_get_send(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff820702b0-ffffffff8207034f: trace_raw_output_mptcp_subflow_get_send (STB_LOCAL)
ffffffff821375fc-ffffffff82137658: trace_raw_output_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum print_line_t trace_raw_output_mptcp_subflow_get_send(struct trace_iterator *iter, int flags, struct trace_event *trace_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff82144260-ffffffff821442ff: trace_raw_output_mptcp_subflow_get_send (STB_LOCAL)
ffffffff82219487-ffffffff822194e3: trace_raw_output_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
